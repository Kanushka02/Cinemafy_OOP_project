# 🎬 Cinemafy - Movie & TV Series Browsing System

Cinemafy is a web-based application developed as a group project for the **Object-Oriented Programming (OOP)** module at **SLIIT** (2nd Year, 1st Semester).  
The system allows users to browse, review, and rate movies and TV series. It demonstrates the practical application of **OOP principles**, **Java EE (Servlets & JSP)**, and **MySQL** in creating a fully functional, database-driven web application.

---

## 📌 Project Overview

**Technologies Used:**
- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Backend:** Java (Servlets & JSP)  
- **Database:** MySQL  
- **Server:** Apache Tomcat 9.0  
- **IDE:** Eclipse IDE for Enterprise Java Developers  
- **JDK:** Java 22  

---

## 👥 Team Roles

Each member was responsible for a specific module.  
Below is **my contribution** to the project.

---

## 🙋‍♂️ My Contribution

### 1. **User Authentication System**
- Developed **Login** and **Registration** pages using JSP and Servlets.
- Validated user credentials and handled incorrect login attempts with proper feedback messages.
- Stored user details securely in the `users` table.
- Implemented session handling to keep users logged in while browsing.

### 2. **CRUD Operations for User Management**
- Enabled **Create**, **Read**, **Update**, and **Delete** functionality for user profiles.
- Users can update profile details such as name, email, and password.
- Admin users can view and manage all registered users.
- Connected CRUD operations with MySQL using JDBC for seamless data manipulation.

### 3. **Login Validation & Error Handling**
- Implemented server-side form validation for login and registration.
- Displayed error messages for missing or invalid inputs.
- Added logout functionality that properly invalidates sessions.

### 4. **Integration with Other Modules**
- Integrated the authentication flow with other pages such as reviews and home page.
- Ensured restricted pages are accessible only to logged-in users.
- Designed consistent navigation links within the shared header and footer.

---

## 🗃️ Database Schema (Relevant Tables)

### `users`
| Column Name | Data Type | Description |
|--------------|------------|-------------|
| user_id | INT (PK) | Unique ID for each user |
| username | VARCHAR(50) | User’s display name |
| email | VARCHAR(100) | User’s email address |
| password | VARCHAR(255) | Encrypted user password |
| role | VARCHAR(20) | Role (e.g., user/admin) |

Sample records were added for testing login and CRUD functionality.

---

## 🎯 Key Features in My Module

- ✅ User registration and login validation  
- ✅ Session-based authentication  
- ✅ Full CRUD operations for users  
- ✅ Proper error and success message handling  
- ✅ Integration with other site pages (reviews, home, etc.)  

---

## 🚀 How to Run the Project

1. Clone or download the project folder.  
2. Import it into **Eclipse** as a **Dynamic Web Project**.  
3. Set up **Apache Tomcat 9.0** as the application server.  
4. Create a MySQL database named `cinemafy` and run the provided `.sql` file.  
5. Update your database credentials inside the Servlet code (if required).  
6. Run the project on Tomcat and visit:  
   👉 `http://localhost:8080/Cinemafy`

---

## 📅 Submission Details

- **Module:** Object-Oriented Programming (OOP)  
- **Year:** 2nd Year, 1st Semester  
- **Institute:** Sri Lanka Institute of Information Technology (SLIIT)  
- **Submission Type:** Group Project  

---

