# Student Examination Result Processing System

## 📌 Description

A Dynamic Web Application developed using **HTML and Java Servlet** to process student examination results.

The application accepts student details, subject marks, and attendance percentage. It calculates the total and average marks, assigns a grade, checks eligibility, and displays the final Pass/Fail result dynamically.

## 🎯 Features

* Enter Register Number
* Enter Student Name
* Enter Department
* Enter marks for 5 subjects
* Enter Attendance Percentage
* Calculate Total Marks
* Calculate Average Marks
* Assign Grade
* Check Attendance Eligibility
* Determine Pass/Fail status
* Display result in a formatted HTML table

## 🛠️ Technologies Used

* HTML
* Java
* Java Servlet
* Apache Tomcat 10.1
* Eclipse IDE

## 📂 Project Structure

```text
StudentResult/
│
├── Java Resources/
│   └── src/
│       └── student/
│           └── MyServlet.java
│
└── WebContent/
    └── index.html
```

## ⚙️ Result Criteria

### Eligibility

```text
Attendance >= 75% → Eligible
Attendance < 75%  → Not Eligible
```

### Pass Criteria

A student is declared **PASS** when:

* Each subject mark is at least 40
* Overall average is at least 50
* Attendance is at least 75%

Otherwise, the student is declared **FAIL**.

### Grade

| Average  | Grade |
| -------- | ----- |
| 90 - 100 | A+    |
| 80 - 89  | A     |
| 70 - 79  | B     |
| 60 - 69  | C     |
| 50 - 59  | D     |
| Below 50 | F     |

## 🚀 How to Run

1. Open the project in **Eclipse IDE**.
2. Configure **Apache Tomcat 10.1**.
3. Run the project using **Run on Server**.
4. Open `index.html`.
5. Enter the student details and marks.
6. Click **Calculate Result**.
7. The servlet processes the data and displays the examination result.

## 📚 Concepts Covered

* HTML Forms
* GET/POST
* `request.getParameter()`
* `request.getParameterValues()`
* Type Conversion
* Conditional Statements
* Calculations
* Servlet Response
* Dynamic HTML


