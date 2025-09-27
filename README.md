# 👥 Employee Registration Project

This project is designed to register employees in a company and manage them based on their departments.  
Each employee has a **unique ID**, and salary increases are applied using **fixed raise rates** defined per department.  

---

## 📌 Features

- ✅ Each department has its own fixed (final) **raise rate**  
- ✅ Salary raises are applied **based on employee ID**  
- ✅ Every employee is assigned a **unique ID** automatically:  
  - Department Code + (Total Employee Count + 1) + Initials of Full Name  
  - Example: `BTD258CB`  
- ✅ Employees can be listed **by department**  
- ✅ Console output shows only: **ID, Full Name, Salary, and Department Name**  

---

## 📂 Project Structure

- `Employee` class → Stores employee details and contains the `applyRaise()` method  
- `Department` class → Defines department name and raise rate information  
- `Main` class → Manages employee creation, department assignment, and operations  

---

## ▶️ Example Console Output

Employee ID : 'BTD1IK', Full Name : 'Ilker Kula', Salary : '25000', Department : 'Information Technologies'


---

## 📝 License  

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
This project is licensed under the [MIT License](LICENSE).  

