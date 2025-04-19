

### 🔥 **mySQL x javaFX** 

## 🧰 Requirements

- Java JDK 17+  
- JavaFX SDK (download from https://gluonhq.com/products/javafx/)
- MySQL Server & Workbench
- MySQL JDBC Connector (https://dev.mysql.com/downloads/connector/j/)

---

## 📁 Project Structure

```
YOUR_REPO_NAME/
├── src/
│   └── application/
│       └── Main.java
├── application.css
├── README.md
```

---

## 🔐 Features

- JavaFX-based secure UI with VBox layout
- Username, password, and message input
- Connects to MySQL using JDBC
- Prepared Statements to avoid SQL Injection
- Styled with custom CSS

---

## 🧪 How to Run

1. Make sure MySQL is running and a database `cyberdb` exists with a table:

```sql
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50),
    password VARCHAR(50),
    message TEXT
);
```

2. Set your MySQL username and password in `Main.java`:

```java
String user = "root";
String pass = "your_mysql_password";
```

3. Compile and run the JavaFX application. If using CLI:

```bash
javac --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml -cp .:/path/to/mysql-connector.jar src/application/Main.java
java --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml -cp .:/path/to/mysql-connector.jar src.application.Main
```

Replace `/path/to/` with the actual paths to your JavaFX SDK and MySQL Connector `.jar`.

---

## 🧑‍💻 Author

BlackMask-
Cybersecurity Enthusiast  


---

## 🌐 License

This project is open-source under the [MIT License](LICENSE).
```

Let me know if you'd like this pre-filled with your GitHub username or repo name.
