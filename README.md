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
## 4. Daily Sales Panel
Functionality: Displays the sales made during the current day.
## 5. Product & Category Management
Functionality: Allows the admin to add, modify, delete, and display products and categories.
Components:
Product Information Fields: Fields to enter product details.
Category Selection: ComboBox to select or add categories.
Action Buttons: Buttons to add, modify, delete, and display products.
## 6. Sales Report Between Two Dates
Functionality: Generates a sales report for a specified date range using JCalendar.
Components:
Start Date: Date picker to select the start date.
End Date: Date picker to select the end date.
Generate Report Button: Button to display the sales data for the selected date range.
## 7. Sales Report by Category
Functionality: Generates a sales report based on the selected product or category.
Components:
Product/Category Selection: Fields to choose the product or category.
Update Button: Button to refresh and display the report.
## 8. Daily Sales Summary
Functionality: Displays the summary of sales made during the day.
Components:
Action Buttons: Buttons to add, modify, and delete sales records based on product ID and quantity sold.
Usage
Login: Users can log in using their credentials.
Vendor Panel: Vendors can declare sales by entering product details and quantities sold.
Admin Interface: Admins can manage user accounts, products, and categories, and generate sales reports.
Sales Reports: Generate sales reports for specific date ranges or categories to analyze sales performance.
Database Connection
Ensure that the database connection details are correctly configured in the ProduitCategorie.ConnexionBD class to enable seamless interaction with the SQL database.

Exception Handling
The system includes comprehensive exception handling to manage errors related to database connections and data operations, ensuring a smooth user experience.

# Conclusion
This Sales Management System provides a robust solution for managing sales, users, and products within an organization. Its intuitive interface and comprehensive functionalities make it an essential tool for efficient sales management.
Functionality: Allows the admin to manage user accounts.
Components:
Login: Field to enter the username for the new account.
Password: Field to enter the password for the new account.
Role Selection: ComboBox to select the user role (e.g., admin, vendor).
Create Account Button: Button to create a new user account in the database.
