

---

# ⚡ EnergiPay 

**EnergiPay** is a desktop application built using **Java Swing** that simplifies electricity billing and customer management for utility providers.
It offers a smooth graphical interface, secure authentication, and complete billing management — all integrated with a **MySQL database** via **JDBC**.

---

## 🚀 Key Features

1. **User Authentication** – Create secure user accounts for personalized access.
2. **Customer Management** – Add, view, and update customer details easily.
3. **Bill Calculation** – Automatically calculate bills based on consumed units.
4. **Payment Handling** – Manage bill payments within the system.
5. **Bill Generation** – Instantly generate detailed bills for any customer.

---

## 🧠 About the Project

This system was developed in **IntelliJ IDEA** using **Java Swing** for the GUI and **JDBC** for database connectivity.
It’s composed of multiple modular classes, each handling a different function of the billing process:

* **SplashScreen** – Displays the welcome/loading interface.
* **LoginPage** – Handles user authentication and access control.
* **Dashboard** – Acts as the central navigation hub after login.
* **AddCustomer** – Lets users add new electricity connections.
* **PayBill** – Facilitates payment and transaction updates.
* **GenerateBill** – Creates printable customer bills.
* **ViewDetails** – Displays existing customer and billing data.
* **LastBill** – Keeps track of previous bills and payments.
* **DatabaseConnection** – Manages the JDBC link between Java and MySQL.

---

## 🗄️ Database Structure (MySQL)

The database used by **EnergiPay** includes four primary tables:

| Table        | Description                                                           |
| ------------ | --------------------------------------------------------------------- |
| **login**    | Stores user credentials (username, password)                          |
| **bill**     | Contains billing details like meter number, units, month, and amount  |
| **customer** | Keeps customer info such as name, address, city, email, and phone     |
| **tax**      | Stores static tax details like meter rent, GST, service charges, etc. |

Communication between Java and MySQL is handled securely using **JDBC (Java Database Connectivity)**.

---

## 🖥️ Screens Overview

Here’s what you’ll find inside the app:

* **Login Window** – Secure access to the system
* **Main Dashboard** – Central hub for all operations
* **Add Customer Form** – Add or update customer data
* **Bill Calculator** – Compute charges dynamically
* **Customer Details View** – See all records at once
* **Bill Generator** – Create and print customer bills

---

## 🧑‍💻 Author

Developed by **Aishwarya Sharma**

🔗 **Portfolio:** [yeahmeash-portfolio.netlify.app](https://yeahmeash-portfolio.netlify.app)
💼 **LinkedIn:** [linkedin.com/in/aishwarya-sharma-799428205](https://linkedin.com/in/aishwarya-sharma-799428205)
🐙 **GitHub:** [github.com/yeahmeash](https://github.com/yeahmeash)




---

Would you like me to also create a **short version (3-paragraph)** README — for GitHub’s repository summary section (above the fold)?
It helps your repo look cleaner and more professional at first glance.
