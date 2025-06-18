# 🏢 Administrative Office Directory & Birthday Reminder System

This is a full-stack web application developed during my internship at **Indian Oil Corporation Limited (IOCL)**. The system helps manage employee contact details and includes a birthday reminder feature for better internal engagement.

---

## 📁 Project Structure

---

## 💻 Technologies Used

**Frontend:**
- React.js
- JavaScript
- CSS / Tailwind (if applicable)

**Backend:**
- Java Spring Boot
- RESTful APIs

**Tools:**
- Git & GitHub
- Visual Studio Code
- IntelliJ / Eclipse (for backend)

---

## 🔧 Features

- Admin directory listing with divisions and departments
- Birthday reminder system with upcoming birthdays
- Search and filter employees
- Responsive frontend interface
- API-driven architecture

---

## 📸 Project Screenshots

> Below are the screenshots showcasing various pages and functionalities of the project.

---

### 🔐 Login Page

The secure login interface to authenticate users.

![Login 1](./screenshots/login-1.png)  
![Login 2](./screenshots/login-2.png)

---

### 🏠 Home Page

The dashboard displaying key summaries, quick links, and announcements.

![Home 1](./screenshots/home-1.png)  
![Home 2](./screenshots/home-2.png)  
![Home 3](./screenshots/home-3.png)  
![Home 4](./screenshots/home-4.png)  
![Home 5](./screenshots/home-5.png)

---

### 🎂 Birthday Reminder Page

Displays today's and upcoming employee birthdays in a card-based layout.

![Birthday](./screenshots/birthday-1.png)

---

### 🔍 Search Page

Search employees by name, designation, function, division, and more.

![Search 1](./screenshots/search-1.png)  
![Search 2](./screenshots/search-2.png)  
![Search 3](./screenshots/search-3.png)  
![Search 4](./screenshots/search-4.png)  
![Search 5](./screenshots/search-5.png)  
![Search 6](./screenshots/search-6.png)  
![Search 7](./screenshots/search-7.png)  
![Search 8](./screenshots/search-8.png)  
![Search 9](./screenshots/search-9.png)

---

### 📞 Intercom Page

Browse internal contact details such as intercom numbers and office extensions.

![Intercom](./screenshots/intercom-1.png)

---

### 📥 Request Page

Admins can view and act upon profile update requests submitted by users.

![Request 1](./screenshots/request-1.png)  
![Request 2](./screenshots/request-2.png)

---

### 🗑️ Recycle Page

Manages deleted employee profiles with options to restore or delete permanently.

![Recycle 1](./screenshots/recycle-1.png)  
![Recycle 2](./screenshots/recycle-2.png)

---

### 👤 User Profile Page

Displays user profile details with editing options for personal and contact information.

![Profile 1](./screenshots/profile-1.png)  
![Profile 2](./screenshots/profile-2.png)

---

## ⚙️ Project Setup Instructions

This project is divided into two main parts:

- **Frontend** — Built using **React.js**, located in the `OfficeDirectoryFrontend/` folder.  
- **Backend** — Built using **Java Spring Boot**, located in the `OfficeDirectoryBackend/` folder.

To run the project locally, first make sure you have Node.js, npm, Java JDK 17+, Maven, and a database like MySQL installed.

Start by navigating to the `OfficeDirectoryFrontend/` folder in your terminal. Install the required dependencies using `npm install`, then start the development server using `npm run dev`. The frontend will be available at `http://localhost:5173/`.

Next, open the `OfficeDirectoryBackend/` folder in your IDE (such as IntelliJ or Eclipse) as a Maven project. In the `application.properties` file located at `src/main/resources/`, configure your database connection. For example:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_database
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update

Once configured, run the main class IoclBackendApplication.java located at src/main/java/ems/iocl/Backend/. The backend server will start on http://localhost:8080/.
