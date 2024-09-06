# Music Store Database

This project is a simple relational database for a Music Store, implemented using SQL. It allows for managing data related to albums, artists, customers, and purchases in a structured manner, ensuring data integrity and ease of querying.

## Features

- Stores information about Artists, Albums, Customers, and Purchases.
- Supports CRUD operations on the database.
- Proper relationships are established between entities (such as Artist-Album, Customer-Purchase).
- Easy querying to retrieve information like:
  - All albums by a particular artist.
  - Customer purchase history.
  - Available albums in the store.

## Database Schema

The database consists of the following tables:
- **Artists**: Stores information about artists.
- **Albums**: Stores details of albums including the artist and price.
- **Customers**: Stores customer details.
- **Purchases**: Records transactions between the store and customers.

### Schema Diagram

The following diagram represents the structure of the Music Store database schema:

![Schema Diagram](schema_diagram.png)

## Requirements

- MySQL or any SQL database system compatible with standard SQL.
- SQL Workbench or any preferred tool for running SQL scripts.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/ayushchahat/Music_store_database.git
