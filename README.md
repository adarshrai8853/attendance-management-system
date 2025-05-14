# 🎓 Attendance Management System (C++)

## Overview
This **console-based Attendance Management System** helps **students** and **admins** register, log in, and track attendance records. The system uses **file handling** for data storage, making it simple and efficient.

## Features
### 👤 Student Functions:
- **Login** with credentials.
- **Mark attendance** for the day.
- **Check** personal attendance count.

### 🛠️ Admin Functions:
- **Register** new students.
- **View and manage** student records.
- **Delete** student records (individual or all).
- **Check attendance** for students.
- **View a list** of students with their attendance stats.

## 📂 File Handling
- Student data is stored in individual files (`username.dat`).
- A master file (`db.dat`) maintains a list of registered usernames.

## 🏗️ Tech Stack
- **C++** for core development.
- **File handling** (`fstream`) for data storage.
- **Console-based UI** for interaction.

## 🚀 Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/adarshrai8853/attendance-system.git
##  Compile & Run
  ```sh
    g++ attendance_system.cpp -o attendance_system
    ./attendance_system
