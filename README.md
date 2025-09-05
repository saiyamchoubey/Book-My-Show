# 🎬 Book My Show APIs – Spring Boot Project  

This project is a **Spring Boot implementation** of backend APIs for a ticket booking system inspired by the popular platform **BookMyShow**.  
It provides a set of **RESTful APIs** that allow client applications to perform operations like user management, movie and theater management, ticket booking, seat selection, and viewing booking history.  

---

## 🚀 Features  

- **👤 User Management**  
  - Register, log in, and manage user profiles.  

- **🎥 Movie Management (Admin only)**  
  - Add, update, and delete movies.  

- **🏢 Theater Management (Admin only)**  
  - Add new theaters, allocate seats, edit, or remove them.  

- **🎟 Ticket Booking**  
  - Browse available movies and book tickets for shows.  

- **💺 Seat Selection**  
  - Choose preferred seats during ticket booking.  

- **📜 Booking History**  
  - View past bookings with detailed information.  

- **📧 Email Notifications**  
  - Receive confirmations and important updates via email.  

---

## 🛠️ Technologies Used  

- **Java 8+**  
- **Spring Boot**  
- **Spring MVC**  
- **Spring Data JPA (Hibernate)**  
- **MySQL** – database  
- **Maven** – dependency management  
- **SMTP Server** – email notifications  

---

## 📊 Project Flow  

### 🔹 Flowchart  
![BMS Flowchart](![Uploading IMG-20250905-WA0025.jpg…]()
)  

### 🔹 Swagger UI Preview  
![Swagger Screenshot](src/main/java/com/driver/bookMyShow/Images/Book-my-show%20API%27s.png)  

---

## ⚙️ Getting Started  

Follow these steps to set up the project locally:  

1. **Navigate to the project directory**  
   ```bash
   cd book-my-show
   ```
2. **Configure database settings in `application.properties`.**  
3. **Build the project**  
   ```bash
   mvn clean install
   ```
4. **Run the application**  
   ```bash
   mvn spring-boot:run
   ```

---

## 🗄️ Database Setup
This project uses MySQL as the database.
1. Install MySQL on your system.
2. Create a database:
 ```bash
   CREATE DATABASE bookmyshow;
   ```
3. Update `application.properties` with your DB credentials.

   



