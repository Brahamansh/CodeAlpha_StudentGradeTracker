# Student Grade Tracker

A simple Java console application that allows a user to enter student names and grades, then calculates and displays the summary statistics for the class.

## Features

- Enter the total number of students
- Input each student's name and grade
- Calculate:
  - average score
  - highest score
  - lowest score
- Display all student records in a formatted summary table

## Project Files

- `StudentGradeTracker.java` - main Java program
- `Student.class` - compiled Java class file
- `StudentGradeTracker.class` - compiled application class

## How to Run

1. Open a terminal in the project folder.
2. Compile the Java file:

```bash
javac StudentGradeTracker.java
```

3. Run the program:

```bash
java StudentGradeTracker
```

## Example

```text
=== Student Grade Tracker ===
Enter total number of students: 3
Enter name for student 1: Alice
Enter grade for Alice: 85
Enter name for student 2: Bob
Enter grade for Bob: 92
Enter name for student 3: Charlie
Enter grade for Charlie: 78

================ SUMMARY REPORT ================
Student Name         Grade
------------------------------------------------
Alice               85.00
Bob                 92.00
Charlie             78.00
------------------------------------------------
Average Score : 85.00
Highest Score : 92.00
Lowest Score  : 78.00
================================================
```

## Requirements

- Java Development Kit (JDK)
- Command-line terminal or IDE such as VS Code, IntelliJ IDEA, or Eclipse

## Purpose

This project is useful for learning basic Java concepts such as:

- user input with `Scanner`
- arrays/lists (`ArrayList`)
- loops and conditionals
- calculations and formatted console output
