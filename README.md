# 🍔 Online Food Order System

A full-stack **Online Food Ordering System** built using **Spring Boot**, **Angular**, and **MySQL**.  
Implements the **MVC architecture** and integrates REST APIs for seamless client-server communication.

---

## 🚀 Features

- 🔐 User & Merchant Login and Registration
- 🧾 Menu Management (View, Add, Update, Delete)
- 🛒 Add to Cart and Checkout functionality
- 💳 Online Payment Processing Simulation
- 📊 Database Integration using MySQL
- ⚙️ RESTful API communication (Angular ↔ Spring Boot)
- 🧰 Real-time UI updates without page reload

---

## 🧱 Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | Angular 8 (TypeScript, HTML, CSS) |
| Backend | Spring Boot v2.1.6 (Java 8+) |
| Database | MySQL |
| ORM | Java Persistence API (JPA) |
| Communication | REST APIs |
| Architecture | MVC |

---

## 🧰 Prerequisites

- ☕ Java 8 or above  
- 🧩 Node.js & npm  
- 🐬 MySQL Server  
- 🌐 Modern Web Browser

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/MohamadAub/online-food-order-system.git
cd online-food-order-system
```

### 2️⃣ Backend Setup (Spring Boot)
1. Import the project into your preferred IDE (IntelliJ, Eclipse, or Spring Tool Suite).  
2. Update **application.properties** with your MySQL credentials.  
3. Run the project as a **Spring Boot App**.  
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

### 3️⃣ Frontend Setup (Angular)
1. Navigate to the Angular directory.  
2. Install dependencies and run the development server:
   ```bash
   npm install
   ng serve
   ```

### 4️⃣ Database Configuration
Import the provided **MySQL schema** and ensure proper connection between backend and frontend.  
Default ports:
- Angular → `4200`
- Spring Boot → `8080`
- MySQL → `3306`

---

## 👤 Login Details

### Merchant
- **Username:** merchant  
- **Password:** merchant

### User
- **Username:** user  
- **Password:** user

---

## 🧩 Project Structure
```
online-food-order-system/
├── backend/ (Spring Boot Application)
│   ├── src/
│   ├── pom.xml
│   └── application.properties
├── frontend/ (Angular Application)
│   ├── src/
│   ├── package.json
│   └── angular.json
└── README.md
```

---

## 🧠 Learning Outcomes

- Understanding of full-stack development workflow  
- Integration of Angular with Spring Boot via REST APIs  
- Database management using MySQL & JPA  
- MVC architecture design principles

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

---

### 💡 Author
Developed by **Mohamad Aub**  
📧 Contact: [LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/MohamadAub)

