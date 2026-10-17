Restaurant Management & Billing System

📌 Project Overview

Restaurant Management & Billing System is a Python-based console application designed to manage essential restaurant operations such as menu management, customer order processing, automated billing, order history, and sales reporting. The project uses Python, JSON file handling, functions, data structures, exception handling, and datetime operations to create a simple and practical restaurant management solution. The application provides separate options for customers and administrators, allowing menu items to be managed and customer orders to be processed efficiently.

🎯 Project Objective

The main objective of this project is to develop a simple restaurant management application that can: • Manage restaurant menu items and prices. • Allow customers to place orders. • Calculate item-wise totals, subtotal, GST, and grand total. • Generate detailed customer bills. • Store menu and order information using JSON files. • Maintain order history. • Search previous orders using Order ID. • Generate basic sales reports. • Provide an admin panel for menu management.

🚀 Key Features

Menu Management
The system provides an admin panel for managing restaurant menu items. Administrators can: • View menu items • Add new food items • Update existing food items • Delete menu items • Update item prices

Customer Order Management
Customers can: • View available menu items. • Select food items using Item ID. • Enter required quantities. • Add multiple items to an order. • Receive validation for invalid item IDs and quantities.

Automated Billing
The system automatically calculates: Item Total = Price × Quantity

Subtotal = Sum of Item Totals

GST = Subtotal × 5%

Grand Total = Subtotal + GST The generated bill contains: • Order ID • Customer name • Date • Time • Ordered items • Quantity • Item price • Item total • Subtotal • GST • Grand total

Order History
All completed orders are stored in a JSON file. The application allows users to view: • Previous Order IDs • Customer names • Order dates • Order times • Ordered items • Quantities • Grand totals

Order Search
Users can search for a specific order by entering its Order ID. The system retrieves the corresponding order and displays its complete bill.

Sales Report
The application provides a basic sales reporting feature that calculates: • Total Orders • Total Items Sold • Total Sales • Average Order Value This feature demonstrates how transaction data can be converted into useful business metrics.

Data Persistence The project uses JSON files to store application data: menu.json orders.json This allows menu and order information to remain available after the application is closed and restarted.
🛠️ Technologies Used

Programming Language • Python Python Modules • json • os • datetime Concepts Used • Functions • Lists • Dictionaries • Loops • Conditional Statements • Exception Handling • File Handling • JSON Data Storage • CRUD Operations • Data Aggregation • Modular Programming

🖥️ Application Menu

When the program starts, the main menu provides the following options: RESTAURANT MANAGEMENT SYSTEM
View Menu Place Order View Order History Search Order Sales Report Admin Panel Exit

👨‍💼 Admin Panel

The admin panel provides menu management functionality: ADMIN PANEL
Display Menu Add Menu Item Update Menu Item Delete Menu Item Back to Main Menu 📊 Sales Reporting

The sales report provides basic business performance metrics: Total Orders Total Items Sold Total Sales Average Order These metrics can help understand restaurant transaction performance.

🧠 Learning Outcomes

Through this project, I gained practical experience in: • Developing a Python-based business application. • Designing modular functions. • Working with lists and dictionaries. • Implementing CRUD operations. • Reading and writing JSON files. • Handling invalid user inputs. • Performing calculations and data aggregation. • Generating transaction bills. • Creating basic sales reports. • Structuring a complete console-based application.

🔮 Future Enhancements

The project can be further improved by adding: • MySQL database integration. • Login and authentication. • Graphical User Interface using Tkinter. • Restaurant table management. • Inventory management. • Discount and coupon management. • Daily/monthly sales analysis. • Data visualization dashboards. • PDF invoice generation. • Power BI integration for advanced sales analytics. • Customer feedback management.

⭐ Conclusion

The Restaurant Management & Billing System demonstrates how Python can be used to develop a practical business-oriented application. The project combines restaurant menu management, order processing, automated billing, persistent data storage, order tracking, and basic sales analytics into one system. It provides a strong foundation for extending the application into a database-driven restaurant management solution with advanced analytics and visualization capabilities.

👨‍💻 Author Manasi Sawant MBA – (Business Analytics)

Skills Demonstrated Python JSON File Handling Data Structures Exception Handling CRUD Business Reporting Data Analysis
