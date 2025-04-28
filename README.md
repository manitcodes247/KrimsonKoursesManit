# Krimson Kourses - Command-Line Course Manager 🎓

Krimson Kourses is a simple, command-line-based course and student management system. Built in Java, this application enables users to manage courses, students, and assignments through an intuitive CLI interface. It supports adding courses, students, assigning courses to students, and printing details of both courses and students.

## 🚀 Features
- **Add Course**: Add new courses with sequences and validate input.
- **Add Student**: Add new students with unique IDs.
- **Assign Course to Student**: Assign courses to students, ensuring prerequisites are completed.
- **View Student Details**: Print student details including courses assigned.
- **View Course Details**: Print course details including course name and sequence.
- **Exit Application**: Prints summary and stops the application.
- **Request Validation**: Handles invalid commands with appropriate error messages.

## 🛠️ Tech Stack
- Java 17
- Gradle (build tool)
- IntelliJ IDEA (recommended IDE)

## 📂 Project Structure
- `src/main/java/com/krimsonkourses/platform/App.java` – Main application entry point (CLI interface).
- `build.gradle` – Project build configuration.

## 🧩 Supported Commands
| Command                               | Description                                                       |
| ------------------------------------- | ----------------------------------------------------------------- |
| `ADD_COURSE NAME <Course Name> SEQUENCE <Course Sequence>` | Adds a new course to the platform.                               |
| `ADD_STUDENT NAME <Student Name> ID <Student ID>` | Adds a new student to the platform.                              |
| `COURSE_ASSIGN STUDENT <Student ID> COURSE <Course Sequence>` | Assigns a course to a student.                                  |
| `STUDENT_DETAIL <Student ID>`         | Prints details of a specific student.                             |
| `COURSE_DETAIL <Course Sequence>`     | Prints details of a specific course.                              |
| `EXIT`                                | Exits the application and prints a summary.                       |

## 📦 How to Run the Application

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/KrimsonKoursesManit.git
