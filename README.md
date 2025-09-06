# Smart Attendance Tracker

The **Smart Attendance Tracker** is a Java-based application that helps manage and track student attendance efficiently.  
It provides both **console** and **teacher-focused** interfaces, supports database logging, and generates attendance reports.

---

## 🚀 Features
- **Authentication System** for secure access.
- **Student Management** (add, update, view student records).
- **Attendance Recording** with logs stored in a database and log file.
- **Teacher’s App** with grouped daily/weekly attendance summaries.
- **Console-based UI** for quick management.
- **Database Logging** in `attendance.db` and `attendance_log.txt`.
- **Configurable Settings** via `config.properties`.
- **Exportable JAR** for easy execution.

---

## 📂 Project Structure
Attendance/
├── attendance.db # SQLite database
├── attendance_log.txt # Attendance logs
├── build.xml # Apache Ant build script
├── config.properties # Configuration file
├── manifest.mf # Manifest file for JAR
├── dist/
│ └── Attendance.jar # Packaged executable JAR
├── build/classes/com/attendancetracker/
│ ├── auth/ # Authentication logic
│ ├── data/ # Data models (Student, AttendanceRecord, etc.)
│ ├── io/ # Logging utilities
│ ├── network/ # Server & client communication
│ ├── service/ # Core business logic
│ ├── ui/ # Console and Teacher UI
│ └── util/ # Utility functions (Date handling, etc.)


---

## ⚙️ Requirements
- **Java 8 or later**
- **SQLite** (embedded)
- **Apache Ant** (if building from source)

---

## ▶️ How to Run
1. Download or clone this repository.
2. Navigate to the `dist/` folder.
3. Run the application using:

   ```bash
   java -jar Attendance.jar
