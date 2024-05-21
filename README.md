# Gestion-Produit-Stock
Java Sales Management System
Overview
This Java-based Sales Management System project is designed to streamline the process of managing sales, users, products, and categories within an organization. It features a user-friendly interface with multiple panels, including login, vendor, and admin functionalities. The system integrates with an SQL database for secure data storage and retrieval.

# Panels of the Project
## 1. Login Panel
Functionality: Allows users to log in using credentials created by the administrator.
Components:
Login: TextField for entering the username.
Password: PasswordField for entering the password.
Connexion Button: Button that validates the credentials and redirects the user to the assigned panel based on their role.
## 2. Vendor Panel
Functionality: Enables vendors to declare sales.
Components:
Product Name/ID: Fields to enter the product details.
Quantity Sold: Field to input the quantity of products sold.
Submit Button: Button to update the sales data in the database.
Logout Button: Button to log out and return to the login panel.
## 3. Admin Interface
Account Management
Functionality: Allows the admin to manage user accounts.
Components:
Login: Field to enter the username for the new account.
Password: Field to enter the password for the new account.
Role Selection: ComboBox to select the user role (e.g., admin, vendor).
Create Account Button: Button to create a new user account in the database.
