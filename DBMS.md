
# DBMS Concepts and Interview Questions

## Transaction States:

- **Active State:** The active state is the first state of every transaction. In this state, the transaction is being executed.
- **Partially Committed:** The transaction has completed its final operation but is still not fully committed.
- **Committed:** The transaction has been successfully completed and all changes are permanently saved to the database.
- **Failed:** The transaction cannot proceed due to an error or interruption, and it cannot be completed successfully.
- **Aborted:** If the transaction fails in the middle of execution, all executed operations are rolled back to a consistent state.
- **Terminated:** The transaction has completed its lifecycle, either by committing successfully or aborting, and is no longer active.

## DBMS Architecture:

### One-Tier Architecture (Single-Tier):
- All components of the application are installed and run on a single system.

### Two-Tier Architecture (Client-Server):
- Application logic and data storage are separated into client and server.
- **Example:** Online Banking System.

### Three-Tier Architecture:
- The application is divided into three logical tiers: Presentation Layer, Application Layer (Business Logic), and Data Layer.
- **Example:** E-commerce website.

## What is Denormalization?
Denormalization is a technique in a database management system (DBMS) that improves performance by adding redundant data to a normalized database.

## What is a Cursor?
A cursor in DBMS is a temporary memory space that allows developers to access and manipulate individual records in a database row by row.

## Integrity Constraints:

1. **Primary Key Constraint:** Ensures each row is uniquely identified.
2. **Unique Constraint:** Ensures values in a column are unique.
3. **Foreign Key Constraint:** Enforces referential integrity by ensuring that values in a column match values in another table's primary key.
4. **Check Constraint:** Validates data based on a specified condition.
5. **Not Null Constraint:** Ensures that a column cannot contain NULL values.
6. **Entity Integrity Constraint:** Ensures each row is uniquely identifiable.
7. **Referential Integrity Constraint:** Ensures that relationships between tables are maintained.
8. **Domain Constraint:** Defines the permissible values for a column.

## What is Normalization?
Normalization is the process of organizing data to minimize redundancy and avoid data anomalies (insertion, update, and deletion anomalies).

## Types of Join Dependency:

1. **Lossless Join Dependency:** No data is lost when tables are joined.
2. **Lossy Join Dependency:** Data may be lost or duplicated when tables are joined.

## Normal Forms:

1. **1NF:** Contains atomic values.
2. **2NF:** In 1NF and fully dependent on the primary key.
3. **3NF:** In 2NF and no transitive dependencies.
4. **BCNF:** Stronger form of 3NF.
5. **4NF:** In BCNF and no multivalued dependencies.
6. **5NF:** In 4NF and no join dependencies.

## What is a View?
A view is a virtual table that presents data from one or more tables through a single query.

## What is a Materialized View?
A materialized view is a duplicate data table created for faster data retrieval.

## What is a Stored Procedure?
A stored procedure is a group of SQL queries that can be saved and reused multiple times. It enhances efficiency, reusability, and security.

## SQL Set Operations:

1. **UNION:** Combines results of two or more SELECT queries, removing duplicates.
2. **UNION ALL:** Combines results of two or more SELECT queries, including duplicates.
3. **INTERSECT:** Returns common rows between two SELECT queries.
4. **MINUS (EXCEPT):** Returns rows present in the first query but not in the second.

## Concurrency Control Techniques:

1. **Lock-Based Concurrency Control:**
   - Transactions acquire locks on data items to ensure exclusive access.
   - **Two-Phase Locking (2PL):** Locks acquired in two phases (growing and shrinking).
   - **Strict 2PL:** Locks held until the end of the transaction.

2. **Timestamp-Based Concurrency Control:**
   - Assigns a unique timestamp to each transaction and data item to resolve conflicts.
   - **Timestamp Ordering Protocol (TO):** Orders transactions based on their timestamps.
   - **Thomas Write Rule:** Resolves write-write conflicts.

## Locks in DBMS:

1. **Shared Lock (S-Lock):** Allows multiple transactions to read a resource but not write to it.
2. **Exclusive Lock (X-Lock):** Grants exclusive access to a resource.

## Log in DBMS:
A log records all changes made to a database (updates, inserts, deletes).

## Log-Based Recovery Techniques:
Log-based recovery ensures database consistency and helps recover from failures.

## Indexing in DBMS:

- **Purpose:** Improve SELECT query performance by reducing scanned rows.
- **Types:**
  - **Single-Column Index:** Created on a single column.
  - **Composite Index:** Created on multiple columns.
  - **Unique Index:** Ensures uniqueness in columns.

- **Clustered Index:** Determines the order of physical data storage (faster).
- **Non-Clustered Index:** Index stored separately from the actual data.
