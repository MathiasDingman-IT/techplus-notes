# Data and Database Fundamentals

## Critical Data

Critical data is information that is essential to an organisation's operations, security, or legal requirements.

### Characteristics

- Highly important
- Sensitive
- Often protected with encryption and backups
- Difficult or costly to replace

### Examples

- Financial records
- Password databases
- Medical records
- Payroll information

### Risks if Lost or Damaged

- Financial loss
- Security breaches
- Legal consequences
- Operational disruption

---

## Non-Critical Data

Non-critical data is information that is useful but not essential to business operations.

### Characteristics

- Less important
- Easier to replace
- Lower security requirements

### Examples

- Temporary files
- Browser cache
- Draft documents
- Downloaded files

### Risks if Lost

- Minor inconvenience
- Reduced productivity
- Little or no long-term impact

---

# Data-Driven Business Decisions

Modern organisations collect large amounts of data and analyse it using algorithms and software tools.

The information gained from this analysis helps businesses:
- Improve products and services
- Understand customer behaviour
- Reduce costs
- Increase profits

The process of collecting and analysing very large datasets is known as **Big Data**.

---

# Data Monetisation

Data monetisation is the process of generating value or income from data.

### Examples

- Data brokers collect, organise, and sell data to other organisations.
- Individuals may receive rewards, discounts, points, or payments in exchange for completing surveys or sharing data.

---

# Database Concepts

A **database** is a system used to store, organise, and manage structured data.

Databases often use **Structured Query Language (SQL)** and include security measures to protect data.

Data can be entered into a database by:
- Manual input
- Importing spreadsheets
- Online forms
- Other databases

### Queries

A **query** is a request to retrieve, filter, or manipulate data stored in a database.

Most queries are written using SQL.

### Reports

Reports present data from queries in an easy-to-read format, such as:
- Tables
- Charts
- Graphs
- Summaries

---

# Databases vs Spreadsheets

## Spreadsheets (Flat Files)

Spreadsheets are suitable for:
- Small to medium datasets
- Calculations and analysis
- A limited number of users

Examples include:
- Microsoft Excel
- Google Sheets

## Databases

Databases provide:

- Faster processing of large datasets
- Better backup and recovery options
- Improved security
- Controlled data types
- Multi-user access
- Greater scalability

---

## Database Deployment Options

### Offline Databases

- No internet connection required
- Reduced exposure to cyber attacks
- Suitable for isolated environments

### Online Databases

- Accessible over the internet
- Supports multiple users simultaneously
- Allows remote access

### Local Databases

- Stored on a local device or server
- Fast data access
- Greater direct control

### Cloud Databases

- Accessible from almost anywhere
- Highly scalable
- Automatic backup options
- Supports remote working

---

# Database Structures

There are three main types of data structures used in databases.

## Structured Data

Data organised into clearly defined rows and columns.

### Examples

- Customer records
- Payroll systems
- Inventory systems

Structured data is ideal for **relational databases**.

---

## Unstructured Data

Data that does not follow a fixed format or structure.

### Examples

- Images
- Videos
- Audio files
- Social media posts

Technologies such as XML and HTML use tags to help organise some forms of unstructured data.

---

## Semi-Structured Data

Data that does not fit neatly into rows and columns but still contains organisational elements.

### Examples

- JSON
- XML

Semi-structured data is commonly used in **key-value** and **document databases**.

---

# Relational Databases

Relational databases store information in related tables.

## Schema

A **schema** defines the structure and organisation of a database.

## Entity

An **entity** is a person, object, or concept about which data is stored.

### Examples

- Customer
- Product
- Employee

## Attribute

An **attribute** is a piece of information that describes an entity.

### Examples

- Name
- Price
- Date of Birth

## Relationship

A **relationship** describes how entities are connected within a database.

---

## Fields and Records

### Field

A **field** is a single piece of information stored within a table column.

### Record

A **record** is a complete row of data made up of multiple fields.

---

## Keys

### Primary Key

A **primary key** is a unique identifier used to distinguish each record in a table.

Examples:
- Customer ID
- Employee Number

Primary keys prevent duplicate records.

### Foreign Key

A **foreign key** is a field that references the primary key in another table.

Foreign keys help create relationships between tables.

---

## Constraints

Constraints are rules used to maintain data accuracy and integrity.

### Example: NOT NULL

A **NOT NULL** constraint requires a field to contain a value and prevents it from being left blank.

---

# Key-Value Databases

A **key-value database** is a type of non-relational database that stores data as pairs.

### Example

```text
Username = Mathias
```

The key is used to quickly locate the associated value.

---

# Document Databases

A **document database** is a non-relational database designed to store flexible, structured documents.

These databases commonly use:

- JSON
- XML

Document databases are ideal when data does not fit neatly into traditional tables.

---

# Data Backup Concepts

## File Backup

A **file backup** is a copy of important files stored in a separate location to protect against data loss.

### Examples

- Documents
- Photos
- Videos
- Project files

---

## System Backup

A **system backup** is a complete copy of a computer's:

- Operating system
- Applications
- Settings
- User files

This is often called a **system image**.

---

## Restoring Data

**Restoring data** is the process of recovering files, folders, or an entire system from a backup.

### Examples

- Recovering deleted documents
- Restoring a failed operating system
- Recovering data after hardware failure

---

## Backup Storage Locations

Backups can be stored on:

- Local storage
- USB flash drives
- External hard drives
- SD cards
- Network storage (NAS)
- Cloud storage services
