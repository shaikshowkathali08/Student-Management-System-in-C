# Student-Management-System-in-C
Student Management System in C using Linked List Data Structure and File Handling with CRUD operations.

---

1. Features

- Add Student Record
- Display Student Records
- Search Student
- Update Student Details
- Delete Student Record
- Save Data to File
- Load Data from File

---

2. Technologies Used

- C Programming
- Linked List Data Structure
- File Handling

---

3. Concepts Implemented

--> Data Structures
- Singly Linked List

--> C Concepts
- Structures
- Functions
- Pointers
- Dynamic Memory Allocation
- Menu-Driven Programming

--> File Handling
- fopen()
- fclose()
- fprintf()
- fscanf()

---

4. Project Structure

```bash
Student-Management-System/
│
├── student_management.c
├── students.txt
└── README.md
```

---

5. Flowchart

```text
                START
                   |
                   v
      -------------------------
      |  Display Main Menu   |
      -------------------------
                   |
                   v
     --------------------------------
     | 1.Add 2.Display 3.Search    |
     | 4.Update 5.Delete           |
     | 6.Save 7.Load 8.Exit        |
     --------------------------------
                   |
         -------------------
         |      |         |
         v      v         v

     Add Student
         |
         v
  Create New Node
         |
         v
   Insert into List
         |
         v
      Return Menu

-------------------------------------

   Display Students
         |
         v
 Traverse Linked List
         |
         v
 Display Student Data
         |
         v
      Return Menu

-------------------------------------

    Search Student
         |
         v
 Enter Roll Number
         |
         v
 Search in Linked List
         |
   ----------------
   |              |
 Found        Not Found
   |              |
   v              v
Display Data   Show Message
         |
         v
      Return Menu

-------------------------------------

    Update Student
         |
         v
 Enter Roll Number
         |
         v
 Search Student
         |
   ----------------
   |              |
 Found        Not Found
   |              |
   v              v
Update Data   Show Message
         |
         v
      Return Menu

-------------------------------------

    Delete Student
         |
         v
 Enter Roll Number
         |
         v
 Search Student
         |
   ----------------
   |              |
 Found        Not Found
   |              |
   v              v
Delete Node   Show Message
         |
         v
      Return Menu

-------------------------------------

      Save to File
         |
         v
 Write Data into File
         |
         v
      Return Menu

-------------------------------------

      Load from File
         |
         v
 Read Data from File
         |
         v
 Create Linked List
         |
         v
      Return Menu

-------------------------------------

          Exit
           |
           v
          END
```

---

6. How to Run

--> Compile the Program

```bash
gcc student_management.c -o student
```

--> Run the Program

```bash
./student
```

---

7. Sample Menu

```text
===== STUDENT MANAGEMENT SYSTEM =====

1. Add Student
2. Display Students
3. Search Student
4. Update Student
5. Delete Student
6. Save Data to File
7. Load Data from File
8. Exit
```

---

8. Learning Outcomes

- Linked List Operations
- Pointer Manipulation
- Dynamic Memory Allocation
- File Handling in C
- CRUD Operations
- Data Persistence

---

9. Future Improvements

- Sorting Student Records
- Student Login System
- GPA Calculation
- GUI Version
- Database Integration



---Author---
Shaik Showkath ali
