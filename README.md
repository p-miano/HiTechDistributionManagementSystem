# Hi-Tech Order Management System

## Overview

The Hi-Tech Order Management System is a Windows Forms Application designed to manage the inventory and orders for Hi-Tech Distribution Inc., a company that supplies computer science books to colleges and universities in Quebec. This project was developed as part of the Multi-tier Applications Development course at the LaSalle College during the Winter 2024 session.

## Features

### Technical Specifications

- Developed using Microsoft Visual Studio 2022, C#, and SQL Server 2022/2019.
- Utilizes ADO.NET for database programming (both connected and disconnected modes).
- Implements the Entity Framework for managing orders.
- Secure login with username and password authentication.

### User Roles and Operations

1. **MIS Manager (Henry Brown)**
   - Add, update, delete, search, and list user information
   - Add, update, delete, search, and list employee information

2. **Sales Manager (Thomas Moore)**
   - Add, update, delete, search, and list customer information

3. **Inventory Controller (Peter Wang)**
   - Add, update, delete, search, and list book information and related information

4. **Order Clerks (Mary Brown, Jennifer Bouchard)**
   - Add, update, cancel, search, and list customer orders

### Business Rules

- Books must have ISBN, Title, UnitPrice, YearPublished, and Quantity on Hand (QOH) fields.
- Books can have multiple authors and be published by one publisher.
- Authors have unique IDs, first name, last name, and email.
- Customers are colleges and universities with detailed information (name, address, phone, fax, credit limit).
- Orders can be taken via phone, fax, or email and payments are made by direct withdrawal.


## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/p-miano/MultiTier-HiTechDistributionManagementSystem.git

2. Open the project in Microsoft Visual Studio 2022.

3. Restore NuGet packages.

4. Update the database connection string in the app.config file.

5. Build and run the application.

   
## Usage

1. Launch the application.
2. Log in with a valid username and password.
3. Navigate through the various user roles and operations to manage books, customers, and orders.


## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with detailed changes.

   

   
