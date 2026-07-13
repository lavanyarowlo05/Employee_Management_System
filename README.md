# 🏢 Employee Management System

A desktop-based **Employee Management System** built with **Python, PyQt5, SQLite3, and Plotly**. The application provides an intuitive graphical interface to manage employee records, visualize employee statistics, and perform complete CRUD (Create, Read, Update, Delete) operations efficiently.

---

## 📌 Features

- 🔐 Secure Admin Login
- 👨‍💼 Add new employees
- 📋 View all employee records in a table
- 🔍 Search employees instantly
- ✏️ Update employee details
- 🗑️ Delete employee records
- 📊 Interactive employee analytics using Plotly
- 📈 Salary and employee statistics
- 🎨 Multiple UI themes
- 🔤 Change application fonts
- 📧 Send emails directly to employees using Mailjet API
- 🧪 Generate fake employee data for testing

---

## 🛠️ Tech Stack

- **Language:** Python
- **GUI Framework:** PyQt5
- **Database:** SQLite3
- **Visualization:** Plotly
- **Email Service:** Mailjet REST API

---

## 📂 Employee Information

Each employee record contains:

- Employee ID
- First Name
- Last Name
- Age
- Salary
- Position
- Email Address

### Validation

- Minimum Age: **18**
- Maximum Age: **70**
- Employee ID acts as the **Primary Key**.

---

## 📸 Application Screens

- Login Screen
- Employee Dashboard
- Search Functionality
- Update/Delete Records
- Interactive Charts & Reports

*(You can add screenshots inside a `screenshots/` folder and link them here.)*

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Employee-Management-System.git
```

### 2. Navigate into the project

```bash
cd Employee-Management-System
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python MainGUI.py
```

---

## 🔑 Default Login Credentials

| Username | Password |
|----------|----------|
| admin | admin |

---

## 📊 Analytics

The application provides graphical insights such as:

- Total Employees
- Total Salary
- Average Salary by Position
- Salary Distribution
- Employee Statistics

All charts are generated using **Plotly**.

---

## 📧 Email Integration

The system supports sending emails directly to employees using the **Mailjet API**.

Before using this feature:

1. Create a Mailjet account.
2. Generate your API Key and Secret Key.
3. Update the credentials inside:

```
use_jet_mail.py
```

---

## 📁 Project Structure

```
Employee-Management-System/
│
├── MainGUI.py
├── authenticate.py
├── employee.py
├── sqlite_code.py
├── use_jet_mail.py
├── requirements.txt
├── LICENSE.md
└── assets/
```

---

## 📚 Requirements

- Python 3.x
- PyQt5
- SQLite3
- Plotly
- Mailjet REST API

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 🚀 Future Improvements

- Role-based authentication
- Export data to Excel/PDF
- Employee profile images
- Attendance management
- Leave management
- Payroll generation
- Dark/Light theme enhancements
- Cloud database support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.


---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub.
