Name: Mayank raj
Company:CODTECH IT SOLUTION
ID:CT08DS388
Domain: Java programing
Duration:December 2024to January 2025
Mentor:Muzammil Ahmed  


Project Overview:
Add Products: Allows users to add new products to the inventory.
Edit Products: Allows users to edit details of existing products.
Delete Products: Allows users to remove products from the inventory.
Track Inventory: Allows users to view current inventory levels.
Generate Reports: Allows users to generate low-stock alerts and sales summaries.
User Authentication: Ensures only authorized users can manage the inventory.
Technologies Used:
Java Swing for the GUI.
Java collections (ArrayList) for storing product data.
Basic file handling or in-memory management for data persistence (without a database in this example).
Simple authentication system for managing access.


Features Overview:
User Authentication:

Simple login system with a hardcoded username (admin) and password (admin123).
Upon successful login, the inventory management interface is shown.
Product Management:

Users can add, edit, and delete products from the inventory.
Each product has a name, quantity, and price.
Inventory Display:

A JTextArea displays the current inventory with product names, quantities, and prices.
Generate Low-Stock Report:

A report displays products with low stock (quantity less than 10).
GUI with Swing:

The GUI uses Swing components like JTextArea, JPanel, and JButton to provide a simple user interface for interacting with the inventory.
Data Persistence (Not Implemented):

The product list (inventory) is stored in memory. For real-world applications, this would typically be connected to a database or a file system for data persistence.
Example Usage:
Login:

User enters username and password, and upon successful authentication, the inventory interface is displayed.
Managing Products:

Add Product: A new product is entered with its details (name, quantity, price).
Edit Product: A user can modify the product's quantity or price.
Delete Product: A user can remove a product from the inventory.
Low Stock Report:

Products with quantities less than 10 are flagged and displayed in the report.
Conclusion:
This basic inventory management system allows users to manage products, track stock levels, and generate simple reports with a graphical interface using Swing. For full-scale production systems, this application can be extended to include data persistence (e.g., using a database), enhanced security, and more sophisticated reporting features.
