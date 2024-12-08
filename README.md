BANK MANAGEMENT SYSTEM_MENDOZA MAVELL C.


PROJECT OVERVIEW

The Bank Management System exists to provide a user-friendly and efficient platform for managing essential banking operations such as account management, transactions, and financial services. It is designed to enhance user experience and streamline backend processes for both customers and bank staff.

Problem the System Solves
-Inefficiencies in Banking Processes:
Manual banking systems require significant time and effort for basic tasks such as account creation, balance inquiries, and transaction recording.This system automates these tasks, reducing manu al workload and minimizing errors.
-Lack of Accessibility:
Traditional banking systems are often limited to physical bank branches. This system allows users to manage their accounts digitally, increasing accessibility and convenience.
-Improved Customer Experience:
Customers can quickly log in, check balances, apply for loans, deposit funds, and view transaction history—all without visiting a bank branch. This immediate access fosters better customer satisfaction and loyalty.
-Streamlined Financial Operations:
The system automates the recording of transactions, including deposits, microloans, and account updates, ensuring financial records are up-to-date. This supports transparency and easy auditing for the organization.
-State the specific, measurable outcomes the project aims to achieve. Use SMART criteria (Specific, Measurable, Achievable, Relevant, Time-bound).




SMART Criteria Analysis for the Bank Management System
Specific
  The project aims to develop a Bank Management System that provides users with the following functionalities:
-Login/Account Creation: Users can securely log in or create a new account.
-View Account Details: Users can check their balance and account information.
-Apply for Microloans: Users can request loans with the amount recorded in the system.
-Deposit Funds: Users can deposit funds and update their account balance.
-Transaction History: Users can view a detailed history of their transactions.
-The functionalities are targeted toward enabling personal banking operations with user-friendliness and security in mind.

Measurable
  -The success of the project can be evaluated by the following measurable outcomes:
-User Onboarding: At least 95% of users can successfully create accounts and log in without encountering errors.
-Transaction Operations: Users can complete deposits and microloan requests within 1 minute, with 100% accuracy in database updates.
-Error Reporting: Any user input errors (e.g., invalid amounts or missing fields) are detected and properly handled 100% of the time.
-Account Access: Users can access their account details and transaction history seamlessly, with data reflecting up-to-date values.
Achievable
-The project is achievable because:
-Technologies Used: The system relies on well-established tools, such as Tkinter for GUI, MySQL for database management, and Python for back-end logic.
-Scope: The scope is limited to essential banking operations for personal use, making it feasible for a small development team or individual within a reasonable timeline.
-Error Handling: The program uses exception handling to prevent common issues like database connection errors or invalid user inputs.

   Relevant
-The project aligns with the needs of small financial institutions or individuals looking for:
-A simple, standalone system for basic banking operations.
-A user-friendly interface without requiring web-based platforms.
-Secure data handling and record-keeping for personal or institutional banking needs.


II.  PYTHON CONCEPTS AND LIBRARIES


Python Tkinter
	 This is a Python program using tkinter for creating a simple graphical user interface (GUI) to manage a bank system. It allows users to log in, view account details, apply for a microloan, deposit funds, and view transactions. The program interacts with a MySQL database to store and retrieve data related to users and transactions. Below is an explanation of the main components and functionality:
  
1. Database Connection:
The connect_db() function establishes a connection to a MySQL database using mysql.connector. The connection details (host, user, password, and database) are specified in the function.
2. Login Functionality (login_user):
-The login screen prompts the user to enter a username and password (yournewpassword)
-If both fields are filled, the system checks the users table in the MySQL database for matching credentials.
-If the login is successful, it opens the main screen, passing the user's username and user_id to display personalized information.
-If the login fails (invalid credentials), an error message is shown.
3. Main Screen (open_main_screen):
-After a successful login, the main screen is displayed, showing options for the user to:
-View account details
-Apply for a microloan
-Deposit funds
-View transactions
-Log out of the system
-Each option triggers a corresponding function (e.g., view_account_details, apply_microloan, etc.).
-This program simulates a simple banking system with user login, account management, and basic transaction handling, all through a GUI interface. It integrates with a MySQL database for user authentication, storing account balances, and transaction history.
-To run this program, ensure that:
-You have a MySQL database called bank_management_system.
-A users table with columns user_id, username, password, and savings_balance exists.
-A transactions table with columns transaction_id, user_id, transaction_type, amount, and transaction_date is available.

MySQL
         This bank management system, developed using Python's Tkinter for the graphical user interface (GUI) and MySQL as the database backend, allows users to securely log in, view their account details, apply for microloans, deposit funds, and track their transaction history, all while providing functionality for creating new user accounts, with database operations such as user authentication, transaction recording, and updating balances executed through MySQL queries, ensuring a smooth and efficient experience for managing financial activities in a user-friendly environment.


III.  SUSTAINABLE DEVELOPMENT GOALS:

      The code you've provided is part of a Bank Management System that handles user login, account creation, microloan applications, deposits, and transaction history. In terms of aligning this with the Sustainable Development Goals (SDGs), this code would primarily contribute to.
SDG 8: Decent Work and Economic Growth

-Financial Inclusion: The system helps in managing bank accounts, loans, and deposits, which can contribute to financial inclusion by providing essential financial services to individuals. This is especially relevant for people in developing regions who may not have access to traditional banking systems.
-Supporting Small Businesses & Individuals: Through microloan applications, the system can enable small businesses or individuals to access credit for their development or expansion, which supports economic growth.

IV.  PROGRAM/SYSTEM INSTRUCTIONS
      This code implements a Bank Management System using Python's Tkinter for the user interface and MySQL for database connectivity, allowing users to log in, view account details, apply for loans, deposit funds, and view transaction history, while also providing the option to create a new account.  A bank management system program typically follows a structured architecture that integrates several key components, such as user authentication, database management, account handling, transaction processing, and secure access controls, where users can log in to access their accounts, view and modify balances, apply for loans, and perform other banking activities, all while ensuring that data is securely stored and transactions are accurately recorded in the database for seamless interaction and management of the bank's operations.







