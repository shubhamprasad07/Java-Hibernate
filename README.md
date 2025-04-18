# Java-Hibernate CRUD Application

This is a simple Java application demonstrating **CRUD operations** (Create, Read, Update, Delete) using **Hibernate ORM** with a MySQL database. The project serves as a foundational example for beginners to understand how Hibernate integrates with Java to manage persistent data.

## 🚀 Features

- Add new records to the database
- Read and display existing records
- Update specific records
- Delete records from the database
- Uses Hibernate for ORM (Object Relational Mapping)

## 🛠️ Tech Stack

- Java
- Hibernate (ORM)
- MySQL
- Maven (for dependency management)

## 📦 Why Hibernate?

Hibernate is a powerful, high-performance Object-Relational Mapping (ORM) tool for Java. It:
- Maps Java classes to database tables
- Eliminates the need for writing boilerplate SQL
- Manages database connections and transactions
- Handles caching, lazy loading, and query optimization

## 📦 Why Maven?

Maven is used in this project for:
- **Dependency Management**: Easily include libraries like Hibernate and MySQL connectors
- **Build Automation**: Compile, test, and package the project efficiently
- **Project Structure**: Follows a standardized layout for easy collaboration and maintenance

## 📂 Project Structure

```
hibernateapp2/
├── src/
│   └── main/
│       └── java/
│           └── [Your Packages & Classes]
├── hibernate.cfg.xml
├── pom.xml
```

## ⚙️ Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/shubhamprasad07/Java-Hibernate.git
   cd Java-Hibernate
   ```

2. **Configure `hibernate.cfg.xml`**
   * Update the database URL, username, and password
   * Make sure MySQL is running

3. **Build the project**
   ```bash
   mvn clean install
   ```

4. **Run the application**
   You can run the main class from your IDE or use the command line (if configured)

## 📌 Prerequisites

* JDK 8 or above
* MySQL database
* Maven
* An IDE like IntelliJ IDEA or Eclipse (optional)

## 🧠 Learning Purpose

This project is built primarily for educational purposes to demonstrate how:
* Java interacts with databases using Hibernate
* ORM simplifies database management
* CRUD operations work in real-world applications
* Maven simplifies project configuration and dependencies

## 📄 License

This project is open source and available under the MIT License.

Feel free to fork the repo and enhance the application with more features like UI integration, advanced queries, REST APIs, etc.
