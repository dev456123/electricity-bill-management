

# Electricity Billing System  

**Electricity Billing System** is a Java-based GUI application built using Java Swing. The system allows users to perform essential operations such as creating secure logins, adding customers, calculating and paying electricity bills, and generating bills.  

---

## Features  

### User Authentication  
- Secure login creation for users.  

### Customer Management  
- Add and manage customer details.  
- Update customer information.  

### Billing Management  
- Calculate electricity bills based on usage.  
- Pay bills directly through the application.  
- Generate and view detailed bills.  

### Database Integration  
- Uses JDBC to connect and interact with the MySQL database for data storage and retrieval.  

---

## Classes Overview  

The system is composed of 16 classes, each with a specific responsibility:  

1. **Splash Screen**: Displays an introductory animation when launching the app.  
2. **Signup**: Allows new users to create accounts securely.  
3. **Login Screen**: Provides login functionality.  
4. **Project**: Acts as the central hub for accessing various functionalities.  
5. **New Customer**: Facilitates adding new customer records.  
6. **Update Information**: Enables updating existing customer details.  
7. **Pay Bill**: Allows users to process bill payments.  
8. **Generate Bill**: Automates the generation of electricity bills.  
9. **View Information**: Lets users view their stored details.  
10. **Bill Details**: Displays a summary of bill transactions.  
11. **Calculate Bill**: Computes electricity consumption costs.  
12. **Customer Details**: Lists all customers and their information.  
13. **Deposit Details**: Tracks payments and deposits.  
14. **Meter Information**: Manages meter-specific details.  
15. **Paytm**: Integrates payment functionality (example: Paytm integration).  
16. **Connection Setup**: Establishes a connection between the application and the MySQL database using JDBC.  

---

## Technologies Used  

- **Java Swing**: For building the graphical user interface (GUI).  
- **JDBC (Java Database Connectivity)**: To connect and communicate with the MySQL database.  
- **MySQL**: For storing and managing application data.  
- **Eclipse IDE**: Used for developing and testing the application.  

---

## How to Run  

### 1. Clone the Repository  
   ```bash
   git clone https://github.com/your-username/electricity-billing-system.git  
   cd electricity-billing-system  
   ```  

### 2. Set Up the Database  
   - Create a MySQL database using the provided schema file.  

### 3. Configure Database Connection  
   - Edit the `Connection Setup` class to include your MySQL credentials.  

### 4. Run the Application  
   - Open the project in Eclipse IDE.  
   - Compile and run the application.  
