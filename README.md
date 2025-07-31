<h1 align="center">Database Search and Reporting</h1>

## 1. Flat File Systems vs. Relational Databases:

### Structure
- **Flat File Systems:**  
  Data is stored in a single table or text file (such as `.txt` or `.csv`). Each line typically represents a record, and fields are separated by delimiters like commas or tabs. There is no enforced structure or relationships between data entries.

- **Relational Databases:**  
  Data is organized into multiple related tables (relations) with defined schemas. Each table has rows (records) and columns (fields), and tables can be linked using primary and foreign keys.

---

### Data Redundancy
- **Flat File Systems:**  
  High data redundancy. Because there’s no relationship mechanism, repeated data (e.g., customer names) must be entered in every relevant file, increasing the risk of inconsistency.

- **Relational Databases:**  
  Low redundancy. By normalizing data and separating it into related tables, duplication is minimized. Shared data is stored once and referenced across tables.

---

### Relationships
- **Flat File Systems:**  
  No support for data relationships. All data must exist in a single file or duplicated across multiple files without linkage.

- **Relational Databases:**  
  Designed to support relationships through keys. You can create one-to-one, one-to-many, and many-to-many relationships across tables, enabling flexible and powerful data modeling.

---

### Example Usage
- **Flat File Systems:**  
  Simple data storage for small applications, logs, configuration files, contact lists, and temporary data export/import operations.

- **Relational Databases:**  
  Used in business applications, banking systems, online shopping platforms, customer management systems, and any use case requiring structured and interconnected data.

---

### Drawbacks

**Flat File Systems**
- Difficult to scale as data grows
- Poor data integrity
- High chance of anomalies (insertion, update, deletion)
- Difficult to manage concurrency

**Relational Databases**
- Requires a DBMS setup
- Learning curve for database design
- Can be complex for very basic tasks
- Slightly more overhead than simple file storage

---

