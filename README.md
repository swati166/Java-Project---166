# Java-Project---166
Java Assignment
# 🧮 Java Servlet Calculator (Tomcat 9 + Java 8)

A simple web-based calculator built using Java Servlets running on Apache Tomcat.

It performs basic arithmetic operations: **Addition, Subtraction, Multiplication, and Division**.

---

## 🚀 Technologies Used

- Java 8
- Servlet API (javax.servlet)
- Apache Tomcat 9
- HTML (for frontend)
- Eclipse IDE (recommended)

---

## 📁 Project Structure
SimpleServletApp/
│
├── src/
│ └── com/example/servlet/
│ └── CalculatorServlet.java
│
├── WebContent/
│ ├── index.html
│ └── WEB-INF/
│ └── web.xml (optional if using annotations)

---

## ⚙️ Features

- Handles both **GET and POST requests**
- Performs:
  - Addition (+)
  - Subtraction (-)
  - Multiplication (*)
  - Division (/)
- Validates user input
- Prevents division by zero
- Displays result in browser

---

## 🧾 CalculatorServlet Code Mapping

```java
@WebServlet("/calculate")
