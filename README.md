# 📚 Library Management System  

## **📖 Overview**  
This web-based Library Management System streamlines library operations, including managing book inventory, tracking user activity, and recording transactions. Built using **PHP**, **SQL**, and **MySQL**, this system demonstrates robust database management and efficient user interface design.  

## **✨ Features**  
- 📚 **Book Management**: Add, update, and remove books from the inventory.  
- 👥 **User Management**: Maintain user records and track borrowing/return activities.  
- 📊 **Transaction History**: Record and display borrowing and return history for auditing purposes.  
- 🔍 **Efficient Search**: Quickly search for books or users using various filters.  

## **💻 Technologies Used**  
- **Frontend**: 🌐 HTML, 🎨 CSS  
- **Backend**: 🖥️ PHP  
- **Database**: 🗄️ MySQL, SQL  

## **🚀 Setup Instructions**  

### **1. Clone the Repository**  
```bash  
git clone https://github.com/JanaviN7/Library-Management-System.git  
cd Library-Management-System  
```  

### **2. Set Up the Database**  
1. Install MySQL or any compatible database management system.  
2. Create a new database (e.g., `library_db`).  
3. Import the provided `library.sql` file into your database using the command line or a GUI tool like phpMyAdmin:  
   ```sql  
   mysql -u username -p library_db < library.sql  
   ```  

### **3. Configure the Application**  
1. Open the `config.php` file in the project directory.  
2. Update the database connection details:  
   ```php  
   $host = "localhost";  
   $username = "your_username";  
   $password = "your_password";  
   $database = "library_db";  
   ```  

### **4. Launch the Application**  
1. Set up a local server using tools like **XAMPP** or **WAMP**.  
2. Place the project files in the `htdocs` directory of your server.  
3. Start the server and navigate to `http://localhost/Library-Management-System` in your browser.  

## **🔮 Future Enhancements**  
- 🔑 Add user authentication for role-based access (admin vs. user).  
- ⏰ Implement a notification system for overdue books.  
- 📊 Integrate analytics to visualize library usage statistics.  

## **📜 License**  
This project is currently not licensed.  

## **🤝 Contributing**  
Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.  

