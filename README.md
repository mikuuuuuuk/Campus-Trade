# Campus Trade System 

A web-based marketplace platform designed for university students to trade second-hand items and services. This project was developed during my freshman year to practice full-stack logic and relational database management.

# Project Scope
* **Marketplace Logic:** Facilitates item listing, browsing, and transaction management.
* **Rating System:** Includes a feedback mechanism to track user reliability after transactions.
* **Data Integrity:** Focuses on maintaining a consistent state between user accounts, product listings, and order history.

# Repository Contents
* `campus_trade_final_v80_schema_FK_SAFE.sql`: The database schema file. It includes Foreign Key constraints to ensure data consistency and prevent orphaned records.
* `v80_order_rating_patch_FULL`: Contains the core application logic and implementation for the order processing and rating modules.

# Technical Implementation
* **Database:** MySQL
* **Key Features:**
  * Relational database design with Foreign Key safety.
  * Automated status updates for orders.
  * Implementation of a user reputation system based on transaction feedback.

# Setup Instructions
1. Import the provided `.sql` file into a MySQL environment.
2. Configure the application connection strings to point to the local database instance.
3. Deploy the source files to a compatible web server environment.
