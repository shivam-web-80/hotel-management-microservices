# 🏨 Hotel Management Microservices

A scalable **microservices-based hotel management system** built using **Spring Boot & Spring Cloud**, designed to handle hotel bookings, user management, ratings, and distributed service communication.

---

## 🚀 Features

### 👤 User Service

* User registration & authentication (OAuth 2.0)
* Book & cancel hotel rooms
* Wallet system for transactions

### 🏨 Hotel Service

* Add and manage hotels
* Add rooms to hotels
* View available & booked rooms

### 📅 Booking Service

* Create and manage bookings
* Retrieve booking details

### ⭐ Rating Service

* Add reviews & ratings
* Fetch ratings by user or hotel

### ⚙️ Infrastructure Services

* Service Registry (Eureka)
* API Gateway
* Config Server (centralized config)

---

## 🛠️ Tech Stack

* **Backend:** Java, Spring Boot, Spring Cloud
* **Security:** Spring Security, OAuth 2.0
* **Service Discovery:** Netflix Eureka
* **Gateway:** Spring Cloud Gateway
* **Database:** MySQL, MongoDB
* **Other:** REST APIs, JPA, Git

---

## 📦 Microservices Architecture

* API Gateway → Entry point
* Eureka Server → Service discovery
* Config Server → Central config
* User Service
* Hotel Service
* Booking Service
* Rating Service

---

## ⚙️ Getting Started

### 🔧 Prerequisites

* Java 17+
* Maven
* MySQL & MongoDB
* Git

---

## 📥 Installation

```bash
git clone https://github.com/your-username/Hotel-Management-Microservices.git
cd Hotel-Management-Microservices
```

---

## ⚙️ Configuration

* Update `application.properties` for:

  * Database credentials
  * Ports
  * Service names

---

## ▶️ Running the Project

Start services in this order:

1. Config Server
2. Eureka Server
3. API Gateway
4. Other Microservices

---

## 📊 Service Monitoring

Eureka Dashboard:
👉 http://localhost:8761

API Gateway Base URL:
👉 http://localhost:8086

---

## 🔗 API Endpoints (Sample)

### 👤 User Service

* Register → `/users/register`
* Login → `/auth/login`
* Book Room → `/users/addBooking`

### 🏨 Hotel Service

* Get Hotels → `/hotels/all`
* Add Hotel → `/hotels/add`

### ⭐ Rating Service

* Add Rating → `/ratings/add`
* Get Ratings → `/ratings/all`

---

## 🔐 Authentication

* Uses OAuth 2.0
* Get token from:

```
/auth/login
```

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first.

---

## 📄 License

Licensed under the MIT License.
