# Payroll System (Java)

A simple Java console application demonstrating **OOP concepts** by managing a payroll system.  
You can add employees (full-time / part-time), calculate their salary, display all employees, and remove an employee by ID.

---

## ✨ Features
- Add **Full-time Employee** with fixed monthly salary  
- Add **Part-time Employee** with hourly rate × hours worked  
- Display all employees with salary details  
- Remove employee by ID  

---

## 🧠 OOP Concepts Used
- **Abstraction** → `Employee` is an abstract class with `calculateSalary()` method  
- **Inheritance** → `FullTimeEmployee` & `PartTimeEmployee` extend `Employee`  
- **Polymorphism** → Different implementations of `calculateSalary()`  
- **Encapsulation** → Private fields + getters  

---

## 📂 Project Structure
```
src/
├─ Main.java
├─ Employee.java
├─ FullTimeEmployee.java
└─ PartTimeEmployee.java
```

*(If you have everything in a single file, that’s also fine.)*

---

## 🛠 Requirements
- Java 8 or higher  
- Any IDE (IntelliJ IDEA recommended) or command line  

---

## 🚀 How to Run

### Option 1: Command Line
```bash
# Compile
javac Main.java
# Run
java Main
```

### Option 2: IntelliJ IDEA
1. Open project in IntelliJ  
2. Right-click `Main.java` → **Run 'Main'**  

---

## 🖥 Example Output
```
Initial Employee Details:
Employee [name=John Doe, id=101, salary=5000.0]
Employee [name=Jane Smith, id=102, salary=450.0]

Removing Employee...

Remaining Employee Details:
Employee [name=Jane Smith, id=102, salary=450.0]
```

---

## ✅ Future Improvements
- Split classes into separate files (if not already)  
- Add menu-driven CLI for user input  
- Save employee data into file or database  
- Add JUnit test cases  

---

## 📄 License
This project is licensed under the **MIT License**.  

---

⭐ If you like this project, consider giving it a star on GitHub!
