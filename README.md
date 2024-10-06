# Hospital Management System (HMS) Project

The **Hospital Management System (HMS)** is a Java-based terminal project designed to streamline the basic operations of a hospital. The system supports three types of users: **Admin**, **Doctor**, and **Patient**, each with distinct roles and functionalities. The primary goal of the system is to efficiently manage appointments, user accounts, and administrative tasks without the use of a database (for now).

This project will help your team understand core concepts like object-oriented programming, user management, role-based access, and appointment scheduling, while building a system that could later be expanded to include additional features.

---

## Key Features

### 1. User Role Management

-  **Admin**: Admins can manage hospital staff (doctors) and patients. They can add, edit, or delete user accounts, view all users, and monitor the system's performance through reports and statistics.
-  **Doctor**: Doctors can view their daily schedules, check patient appointments, and update the status of appointments (e.g., completed or canceled). This helps them efficiently manage their day-to-day consulting activities.

-  **Patient**: Patients can create accounts, log in, and schedule appointments with available doctors. They can view their appointment history and cancel appointments if necessary.

### 2. Appointment Management

-  Patients can book appointments with doctors. The system checks for availability to avoid conflicts.
-  Doctors can view their scheduled appointments for a specific day and update their status as needed.
-  Admins can monitor all appointments in the system to ensure smooth operations.

### 3. System Reports & Statistics (Admin)

-  Admins can view reports on the number of patients, doctors, and appointments to gain insights into hospital performance.
-  This data helps admins make informed decisions and improve hospital efficiency.

### 4. Command-Line Interface

-  The project is fully terminal-based, allowing users to interact with the system through text inputs. This makes it simple to run and ideal for beginners who want to focus on core functionality without needing a graphical interface.

---

## Getting Started

1. **Clone the repository**.
2. **Compile the Java files** inside the `src/` directory.
3. **Run the `Main.java` file** to start the terminal-based application.

---

## Future Potential

While this project currently operates without a database, it has been designed with flexibility to expand. In the future, a database can be integrated to store user and appointment data persistently. Additional features like billing, patient medical records, and notifications can also be added.

This system introduces your team to core software engineering concepts and provides a stepping stone to more complex systems in the future.
