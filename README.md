# IT202-mja65-Project

Overview
This is a PHP-based web application for managing products and shipping operations. It's a project management system designed for inventory and logistics coordination, likely built as an academic IT project (IT202 course).

Key Features
Core Functionality
User Authentication

login.php - User login system
authenticate.php - Authentication validation
logout.php - Session termination
Product Management

product.php - Main product listing and management
create.php - Create new products
create_validation.php - Validate product data on creation
details.php - View product details
deleteProduct.php - Delete products
Shipping Management

shipping.php - Incoming/inventory shipping management (9.4 KB)
shipping_out.php - Outgoing/fulfillment shipping (5.6 KB)
Additional Features

admin.php - Administrative panel
managers.php - Manager access control
home.php - Dashboard/home page
delete.js - Client-side deletion functionality
Backend & Database
Database Connection: njit_database.php - Connects to NJIT database system
Error Handling: database_error.php - Database error management
Styling: main.css - Application CSS styling
Purpose
This is a product/inventory management system with capabilities for:

Creating and managing product catalogs
Tracking incoming and outgoing shipments
Managing user roles (admins, managers, users)
Viewing detailed product information
Administrative oversight of inventory operations
The system is designed for small-to-medium scale product management operations, likely used in a warehouse or logistics context.

