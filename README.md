# University Student Management System

## Project Overview

The University Student Management System is a Java console-based application developed to demonstrate the practical use of fundamental data structures.

The system manages university student records and represents connections between campus locations.

## Data Structures

The project implements:

- Linked List
- Stack
- Queue
- Binary Search Tree (BST)
- Hashing
- Graph
- BFS/DFS Traversal

## Student Information

Each student record contains:

- Student ID
- Name
- Programme
- Marks

## Team Members

| Name | Student ID | Role | Responsibility |
|------|------------|------|----------------|
| M. K. S. S. Ananda | 22UG3-0184 | Project Coordinator | Integration, GitHub documentation and testing |
| M.P.J.S.S. Jayasooriya | 22UG3-0051 | Software Developer 01 | Student Records and Linked List |
| S. D. D. A. Siyambalapitiya | 22UG3-0270 | Software Developer 02 | Stack, Queue, BST and Hashing |
| T. Dhammika Thero | 22UG3-0570 | Software Developer 03 | Graph and BFS/DFS |

## Technologies

- Java
- Git
- GitHub
- Visual Studio Code

## Individual Contributions

### Member 1 - M.P.J.S.S. Jayasooriya (22UG3-0051)
Responsible for the shared `Student` model, the manually implemented singly linked list, student CRUD operations, input validation, and the linked-list test harness.

### Member 2 - S. D. D. A. Siyambalapitiya (22UG3-0270)
**Components Implemented:**

1. **Stack (ActionStack.java)**
   - Maintains recent actions (Undo/History feature)
   - Uses LIFO (Last In First Out) principle
   - Operations: push, pop, peek, isEmpty, displayAll
   - Records every student operation (add, update, delete)

2. **Queue (ServiceQueue.java)**
   - Manages student service requests in order of arrival
   - Uses FIFO (First In First Out) principle
   - Operations: enqueue, dequeue, peek, isEmpty, displayAll

3. **Binary Search Tree (StudentBST.java)**
   - Organizes and searches student records by Student ID
   - Operations: insert, search, delete, displayInOrder, count
   - Displays students in sorted order by Student ID
   - Handles all three deletion cases (leaf, one child, two children)

4. **Hash Table (StudentHashTable.java)**
   - Efficient Student ID searching
   - Uses chaining (Linked List) for collision handling
   - Hash function: (hashValue * 31 + char) % capacity
   - Operations: insert, search, delete, display
   - Provides O(1) average time complexity for searching

**Integration:**
- Integrated all four components into `Main.java`
- Connected Stack, Queue, BST, and Hash Table with student operations
- Tested all menu options successfully

### Member 3 - T. Dhammika Thero (22UG3-0570)
Graph implementation, campus locations, connections, and BFS/DFS traversal.

## How to Run

### Prerequisites
- Java JDK 17 or higher installed

### Steps

1. Open Command Prompt in the `src` folder


s2. Compile all Java files:

3. Run the application:


## Project Structure

## Testing Evidence

All components were tested successfully:
- Stack displays recent actions in LIFO order
- Queue processes service requests in FIFO order
- BST displays students in sorted order by Student ID
- Hash Table searches students in O(1) time
- All CRUD operations work correctly
- Error handling works for invalid inputs

## GitHub Collaboration

- Branch: `member2-stack-queue-bst-hashing`
- Commits: Initial commit + Stack/Queue/BST/Hashing implementation
- Pull Request: Created to merge into main branch

## Acknowledgments

This project was developed as part of the CIT300 Data Structures and Algorithms module at SLTC.