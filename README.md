# Java Assignment 2 – Strings and Collections

**Name:** Prartana  
**Register Number:** 192421099  
**Course:** Programming in Java  
**Assignment:** Assignment 2 (CO2)

## About This Assignment

This assignment is based on Java Strings and Collections. I worked on seven tasks to understand how different Java classes and data structures work and how their performance changes depending on the situation.

For each task, I wrote and executed Java programs, observed their outputs and compared the results wherever required.

## Folder Structure

```text
CSA09-192421099-Assignment2/
│
├── Task01/
├── Task02/
├── Task03/
├── Task04/
├── Task05/
├── Task06/
├── Task07/
├── Screenshots/
├── ExperimentalData/
└── README.md
```

## What I Did in Each Task

**Task 01 – String Performance**

Compared String, StringBuilder and StringBuffer to see how they perform when building text with different numbers of fields.

**Task 02 – Playlist Management**

Used ArrayList and LinkedList to perform operations such as adding, removing, accessing and displaying songs. I also tried ArrayDeque for managing an Up Next queue.

**Task 03 – Student Attendance**

Worked with HashSet to avoid duplicate student records. I also tested how equals() and hashCode() affect duplicate detection.

**Task 04 – Pharmacy Inventory**

Compared HashMap, TreeMap and LinkedHashMap for storing medicine details, searching for stock and displaying records in different orders.

**Task 05 – Generic Leaderboard**

Created a leaderboard that can rank different types of objects using Comparator and generic classes.

**Task 06 – Hospital Emergency Triage**

Used PriorityQueue to arrange patients based on their severity. When two patients have the same severity, the one who arrived first is treated first.

**Task 07 – Redesign and Performance Comparison**

Revisited the playlist implementation from Task 02. I compared repeated LinkedList index access with iterator-based traversal to understand how changing the approach affects performance.

## Software Used

- Java (JDK 27)
- Visual Studio Code
- Windows PowerShell

## How to Run the Programs

Open the project folder in VS Code and open the terminal.

For example, to run Task 01:

```powershell
javac .\Task01\StringBenchmark.java
java -cp .\Task01 StringBenchmark
```

The same method can be followed for the other task files by changing the folder and class names.

## Results and Screenshots

The output screenshots for the programs are stored in the Screenshots folder. Experimental results and timing observations are stored in the ExperimentalData folder.

## Conclusion

By completing these tasks, I got practical experience with different Java collection classes and their uses. I also understood that choosing a data structure depends on the type of operations being performed. Comparing the execution times helped me understand the difference between theoretical time complexity and actual program performance.

