# Blog App  

Blog App is a modern web application that allows users to create blog posts, interact with other users, and manage content efficiently. This project is built with a robust backend infrastructure using cutting-edge technologies.  

---

## 🚀 Features  
- **User Management:** User registration, login, roles, and authorization (JWT-based).  
- **Blog Management:** Adding/editing posts, categories, tags, and comments.  
- **Notification System:** Keep users updated with activity notifications.  
- **Follow and Reporting System:** User follow feature and reporting inappropriate content.  
- **AWS S3 Integration:** Secure file upload and storage for images.  
- **Open API Support:** Comprehensive API documentation with OpenAPI.  

---

## 🛠️ Technologies Used  

### Backend  
- **Spring Boot Framework**  
- **Spring Security**: Authentication and authorization.  
- **Spring Data JPA**: ORM for database operations.  
- **Validation**: Input validation and error handling.  
- **JWT (JSON Web Tokens)**: Token-based secure API access.  
- **ModelMapper**: DTO and Entity transformation.  

### Database  
- **PostgreSQL**: A powerful, open-source relational database management system.  

### Storage  
- **AWS S3**: Secure cloud storage for media files.  

### Others  
- **Lombok**: Simplifies boilerplate code with getter, setter, and other helper methods.  
- **OpenAPI/Swagger**: API documentation and testability.  

---

## 🗂️ Data Models (Entities)  

- **User:** User details and roles.  
- **Role:** User roles (e.g., Admin, User).  
- **Post:** Blog posts.  
- **Category:** Categories for posts.  
- **Tag:** Tags associated with posts.  
- **Comment:** User comments on posts.  
- **Bookmark:** Posts saved by users.  
- **Follow:** User relationships for the follow system.  
- **Notification:** Notifications sent to users.  
- **PhotoFile:** Image files stored in AWS S3.  
- **Profile:** User profiles and details.  
- **Report:** Reporting system for inappropriate content.  

---

## 📖 Setup  

### 1. Prerequisites  
- Java 17 or higher  
- Maven or Gradle  
- PostgreSQL  
- AWS account (for S3)  

### 2. Clone the Repository  
```bash
git clone https://github.com/username/blog-app.git
cd blog-app
