# **Movie Management Application**

This is a web-based project designed for managing movies and user interactions. The application implements a **Spring Boot backend** with **MongoDB** for data storage and a **React-based frontend**. It includes HTML templates for user management, styled with CSS and Bootstrap, and JavaScript for form validation and interactivity.

---
## 🎬 Project Demo

<p align="center">
  <img src="assets/movie-demo.gif" width="850" alt="Movie App Demo"/>
</p>

<p align="center">
  A quick walkthrough of login, browsing movies, and adding reviews.
</p>

## **Features**

### **User Management**
- **Login and Registration Pages**: Created using JSP with proper form fields for username, password, and email.
- **User Dashboard**: Displays user-specific information and interactions.
- **Validation**: JavaScript-based form validation to ensure secure and error-free inputs.

### **Movie Management**
- List of movies with details and posters retrieved from MongoDB.
- Add reviews and ratings for movies.
- Responsive and visually appealing interface.

---

## **Technologies Used**

### **Backend**
- Spring Boot (Java)
- MongoDB (Database)
- Maven (Build Tool)
- JSP for user management templates

### **Frontend**
- React.js for dynamic UI
- Bootstrap for styling and responsiveness
- JavaScript for form validation and interactivity


---

## **Key Functionalities**

### **1. HTML Templates for User Management**
- Professionally structured using JSP and React.
- Semantic HTML ensures clarity and accessibility.
- Templates: `login.jsp`, `register.jsp`, `dashboard.jsp`

### **2. CSS and Bootstrap Styling**
- Consistent and responsive UI using Bootstrap.
- Custom CSS added for enhanced aesthetics.

### **3. JavaScript Validation**
- **Login Page Validation**: Validates username and password fields.
- **Registration Page Validation**: Ensures email format, password strength, and required fields.
- Real-time feedback for user inputs.

---

## **How to Run the Project**

### **Backend**
1. Navigate to the `backend` folder.
2. Run the Maven command:  
   ```bash
   mvn spring-boot:run
   ```

### **Frontend**
1. Navigate to the `frontend` folder.
2. Install dependencies:  
   ```bash
   npm install
   ```
3. Start the React app:  
   ```bash
   npm start
   ```



---

## **Validation and Testing**
- Tested for cross-browser compatibility.
- Verified responsiveness across devices using Chrome DevTools.
- Form validation and interactivity thoroughly checked.

---
