# CCRM
# Campus Course & Records Manager (CCRM)

## 📘 Project Overview

The **Campus Course & Records Manager (CCRM)** is a console-based Java application designed to help educational institutes manage students, courses, enrollments, grades, and file operations. It is built using **Java SE** and follows object-oriented principles, modern I/O operations, and design patterns.

### 🚀 Features

- **Student Management**: Add, update, list, and deactivate students.
- **Course Management**: Create, update, search, and filter courses.
- **Enrollment & Grading**: Enroll/unenroll students, record marks, compute GPA, and generate transcripts.
- **File Operations**: Import/export CSV-like files, backup data with timestamped folders.
- **CLI Interface**: Menu-driven console for all operations.

---

## 🛠️ How to Run

### Prerequisites
- **JDK 17** or later
- Eclipse IDE (or any Java-supported IDE)

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ccrm-project.git
   ```
2. Open the project in Eclipse:
   - `File → Import → Existing Projects into Workspace`
3. Navigate to the main class:
   - `edu.ccrm.cli.CCRMMain`
4. Run the application:
   - Right-click → `Run As → Java Application`

---

## 📚 Java Evolution (Timeline)

- **1995**: Java 1.0 released
- **2004**: Java 5 (Generics, Enums, Autoboxing)
- **2014**: Java 8 (Lambdas, Streams, Date/Time API)
- **2021**: Java 17 (LTS, Sealed Classes, Pattern Matching)

---

## ☕ Java Platforms: ME vs SE vs EE

| Platform | Purpose | Use Case |
|----------|---------|----------|
| **Java ME** | Micro Editions | Embedded systems, mobile devices |
| **Java SE** | Standard Edition | Desktop, console applications |
| **Java EE** | Enterprise Edition | Web apps, distributed systems |

This project uses **Java SE**.

---

## 🏗️ Java Architecture

- **JDK**: Development kit (compiler, tools)
- **JRE**: Runtime environment (libraries, JVM)
- **JVM**: Executes bytecode

> JDK includes JRE, which includes JVM.

---

## 💻 Java Installation on Windows

1. Download JDK from [Oracle](https://www.oracle.com/java/technologies/javase-downloads.html)
2. Run the installer
3. Set `JAVA_HOME` environment variable
4. Add `%JAVA_HOME%\bin` to `PATH`
5. Verify installation:
   ```bash
   java -version
   ```

---

## 🔧 Eclipse Setup

1. Download Eclipse IDE from [eclipse.org](https://www.eclipse.org/downloads/)
2. Extract and run `eclipse.exe`
3. Create a new Java project:
   - `File → New → Java Project`
4. Import source files into `src/` folder

![Eclipse Setup Screenshot](./screenshots/eclipse-setup.png)

---

## 📁 Project Structure

```
edu.ccrm/
├── cli/           # Command-line interface
├── domain/        # Entities (Student, Course, etc.)
├── service/       # Business logic
├── io/            # File I/O operations
├── util/          # Utilities (validators, recursion)
└── config/        # Singleton configuration
```

---

## 🧪 Syllabus Topic Mapping

| Topic | Demonstrated In |
|-------|-----------------|
| OOP Pillars | `domain/Person`, `Student`, `Instructor` |
| Streams API | `service/CourseService.searchCourses()` |
| NIO.2 | `io/BackupService` |
| Design Patterns | `config/AppConfig` (Singleton) |
| Lambdas | `util/Comparators` |
| Recursion | `util/FileUtils.calculateDirectorySize()` |

---

## ⚙️ Enabling Assertions

Add VM argument in Eclipse:
```
-ea
```
Or run via command line:
```bash
java -ea -jar ccrm.jar
```




## 🙏 Acknowledgments

References used:
- Oracle Java Documentation
- Stack Overflow for specific exception handling examples

> This project was developed as part of the Java Programming course. All code is original unless otherwise cited.



---

**⭐ If you find this project useful, please give it a star!**
