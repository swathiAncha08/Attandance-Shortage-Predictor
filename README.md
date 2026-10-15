# 📊 Attendance Shortage Predictor

A simple, colourful, and user-friendly Java desktop application that helps students monitor their attendance and predict how many consecutive classes they need to attend to reach the required **75% attendance target**.

## 📌 About the Project

Maintaining the minimum attendance percentage is important for college students. Sometimes, students find it difficult to calculate their attendance percentage and understand how many more classes they need to attend to meet the required criteria.

The **Attendance Shortage Predictor** solves this problem through a graphical user interface (GUI). Students can add subjects, track attended and total classes, record their daily attendance, and predict the number of consecutive classes required to achieve the 75% target.

## ✨ Features

- **📚 Subject Management:** Add multiple subjects and track attendance separately.
- **📈 Attendance Tracking:** View the total classes, attended classes, and attendance percentage for each subject.
- **🎯 Shortage Prediction:** Calculate how many consecutive classes must be attended to reach 75% attendance.
- **📝 Record Attendance:** Mark the latest class as Present or Absent.
- **📊 Visual Dashboard:** View attendance information using progress bars and summary cards.
- **⚠️ Attendance Monitoring:** Identify subjects where attendance is below the required percentage.
- **🖥️ User-Friendly Interface:** Interact with the application through a Java Swing graphical interface.

## 🛠️ Technologies Used

- **Java** — Core programming language
- **Java Swing** — Graphical user interface
- **HashMap** — Store and manage subject-wise attendance data
- **Object-Oriented Programming (OOP)** — Organize subjects and application logic
- **Eclipse IDE** — Development environment

## ⚙️ How It Works

1. Add a subject, such as Mathematics or Java.
2. Enter the total number of classes conducted and the number of classes attended.
3. View the calculated attendance percentage.
4. Check whether your attendance meets the 75% requirement.
5. If your attendance is below 75%, use the prediction feature to find the number of consecutive classes you need to attend.
6. Record future attendance as Present or Absent to update the dashboard.

## 🧮 Attendance Calculation

The attendance percentage is calculated using:

**Attendance Percentage = (Attended Classes / Total Classes) × 100**

For example, if a student attends 18 out of 24 classes:

Attendance Percentage = (18 / 24) × 100 = **75%**

### Example of Shortage Prediction

Suppose a student attended 18 out of 30 classes.

- Current attendance: 60%
- Required attendance: 75%
- Consecutive classes to attend: 18

The student needs to attend the next 18 classes without missing any to reach 75%.

## 🚀 Getting Started

### Prerequisites

Before running the application, make sure you have:

- Java Development Kit (JDK) installed
- Eclipse IDE or another Java IDE
- Basic knowledge of running Java applications

### Installation

**Step 1: Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/Attendance-Shortage-Predictor.git
```

Replace `YOUR-USERNAME` with your GitHub username.

**Step 2: Open Eclipse**

Launch Eclipse IDE and select your workspace.

**Step 3: Import the project**

1. Click **File → Import**.
2. Select **General → Existing Projects into Workspace**.
3. Choose the project directory.
4. Click **Finish**.

If the project is not recognized as an Eclipse project, create a new Java project and copy the source files into the appropriate `src` folders.

**Step 4: Run the application**

1. Open `src/attendance/Main.java`.
2. Right-click inside the file.
3. Select **Run As → Java Application**.

The Attendance Shortage Predictor dashboard should open.

## 📂 Project Structure

```text
AttendanceShortagePredictor/
├── src/
│   ├── attendance/
│   │   └── Main.java
│   └── module-info.java
├── README.md
└── .gitignore
```

*Note: The exact location of `module-info.java` may vary depending on your Eclipse project structure.*

## 🎯 Project Objectives

- Simplify attendance percentage calculations.
- Help students identify attendance shortages early.
- Predict the number of consecutive classes required to reach the target.
- Demonstrate Java programming, data structures, and GUI development.
- Build a practical project that addresses a real student problem.

## 🔮 Future Enhancements

- Save attendance records permanently using MySQL or a local file.
- Add student login and authentication.
- Generate subject-wise attendance reports.
- Display attendance history and charts.
- Add reminders when attendance falls below the required percentage.
- Export attendance reports to PDF or Excel.
- Support configurable attendance targets for different colleges.

## ⚠️ Current Limitations

- Attendance data is stored in memory and is reset when the application closes.
- The application currently runs as a desktop application.
- Permanent database storage and login functionality are not implemented.

## 👩‍💻 Author

**Swathi Ancha**

B.Tech — Information Technology

GitHub: [Your GitHub Profile](https://github.com/YOUR-USERNAME)



⭐ If you find this project useful, consider giving the repository a star!

**Built with Java to make attendance tracking easier for students.**
