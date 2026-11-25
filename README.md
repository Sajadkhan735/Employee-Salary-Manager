# Employee Salary Manager

**Software Construction & Development Lab (SEC312L)**  
**Lab 7: Open-Ended Lab | Fall 2026**

## 1. Project Overview

Employee Salary Manager is a Java-based console application developed as part of Lab 7. The purpose of this project is to calculate employee salaries based on their working hours, validate employee working hours, and classify employees into different salary categories.

The program uses arrays, loops, conditional statements, and user-defined methods to process employee information and display salary statistics.

## 2. Project Requirements

According to the lab task, the company pays employees Rs. 1,000 per working hour.

- Hourly Rate: Rs. 1,000
- Valid Working Hours: 0 to 60
- High Salary: Rs. 50,000 or above
- Medium Salary: Rs. 30,000 or above
- Low Salary: Below Rs. 30,000

**Note:** In the Git feature-branch task, the Medium salary limit was changed from Rs. 30,000 to Rs. 35,000.

## 3. Main Features

- Calculates employee salaries using working hours.
- Validates working hours between 0 and 60.
- Displays an error message for invalid working hours.
- Categorizes employees as High, Medium, or Low.
- Uses arrays to store employee names and working hours.
- Uses loops to process employee records.
- Calculates the number of valid employees.
- Calculates total salary.
- Calculates average salary using double division.

## 4. Java Methods

The project contains three required methods:

| Method | Purpose |
|---|---|
| calculateSalary(int hours, int rate) | Calculates employee salary |
| getCategory(int salary) | Returns the salary category |
| isValid(int hours) | Checks whether working hours are valid |

## 5. Employee Information

The program uses the following employee records:

| Employee | Working Hours |
|---|---:|
| Hina | 40 |
| Omar | 25 |
| Zara | 70 |
| Bilal | 55 |

Zara's working hours are invalid because they exceed the maximum limit of 60.

## 6. Technologies Used

- Java
- Visual Studio Code
- Windows PowerShell
- Git
- GitHub

## 7. Git and GitHub Implementation

Git was used to manage the project and track changes.

The following Git operations were performed:

1. Initialized a local Git repository using `git init`.
2. Added project files using `git add`.
3. Created the first commit with the message `First commit`.
4. Created a new branch named `feature`.
5. Changed the Medium salary limit to Rs. 35,000.
6. Committed the changes in the feature branch.
7. Switched back to the main branch.
8. Merged the feature branch into main.
9. Connected the local project to GitHub.
10. Pushed the project to the GitHub repository.

### Important Git Commands

```bash
git init
git add Main.java
git commit -m "First commit"
git branch feature
git checkout feature
git add Main.java
git commit -m "Change Medium salary limit to 35000"
git checkout main
git merge feature
git push -u origin main
git log --oneline
```

## 8. How to Run the Project

Make sure Java JDK is installed on your computer.

**Step 1: Clone the repository**

```bash
git clone https://github.com/Sajadkhan735/Employee-Salary-Manager.git
```

**Step 2: Open the project folder**

```bash
cd Employee-Salary-Manager
```

**Step 3: Compile the Java program**

```bash
javac Main.java
```

**Step 4: Run the program**

```bash
java Main
```

## 9. Learning Outcomes

Through this lab task, I learned and practised:

- Writing and calling methods in Java.
- Working with arrays and loops.
- Using conditional statements.
- Validating input data.
- Finding and correcting programming errors.
- Calculating total and average values.
- Understanding Git branches and commits.
- Merging changes between branches.
- Uploading a Java project to GitHub.

## 10. Developer Information

**Name:** M. Sajad  
**Program:** BS Software Engineering  
**Semester:** 6th Semester  
**University:** Iqra University Islamabad  

**GitHub Profile:**  
https://github.com/Sajadkhan735

**Project Repository:**  
https://github.com/Sajadkhan735/Employee-Salary-Manager

## 11. Conclusion

This project helped me improve my understanding of Java programming fundamentals and practical version control using Git and GitHub. It demonstrates how employee salary calculations, validation, and salary classification can be implemented using a simple Java console application.

**Developed for academic learning purposes.**
