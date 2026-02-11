Billing Data Migration Simulator

 Project Overview

This project simulates a real-world billing data migration from a legacy billing system to a clean target database structure (similar to platforms like Chargebee).

It demonstrates end-to-end migration including:

- Data extraction from legacy CSV files
- Data cleaning and transformation
- Schema standardization
- Revenue normalization (integer cents handling)
- Data loading into SQLite
- Reconciliation and validation checks
- Migration summary reporting

The goal of this project is to simulate the responsibilities of a Migration Data Engineer handling large-volume billing data migrations.

 Architecture

Legacy CSV Files  
⬇  
ETL Pipeline (Python + Pandas)  
⬇  
SQLite Target Database  
⬇  
Validation & Reconciliation  
⬇  
Migration Summary Report  

 Features Implemented

- Duplicate removal
- Null handling & data cleaning
- Email standardization
- Date format normalization (ISO format)
- Revenue conversion to integer cents (to avoid float precision issues)
- Row count reconciliation
- Revenue reconciliation
- Basic data integrity validation
- Automated pipeline structure using modular functions


