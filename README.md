# Library_Management_System-

<br> Author: Deviprasad Shetty
<br> 

# Overview
<br> 
<br> This is a command-line-based Library Management System developed in C, designed using core Data Structures such as Linked Lists, Binary Search Trees, and optionally a Stack.
<br> 
<br> The system allows users to perform real-world operations like adding, searching, deleting, borrowing, and returning books — with efficient in-memory handling and a clear, menu-driven interface.
<br> 

# Key Features
<br> 
<br> 1. Add Book
<br> Allows the user to insert a new book (ID, Title, Author) into the library. Books are stored in a Binary Search Tree for fast and sorted access.

<br> 
<br> 2. View Books
<br> Displays all books in ascending order of Book IDs using in-order traversal of the BST.

<br> 
<br> 3. Search Book
<br> Search for any book by its ID using efficient BST search logic.

<br> 
<br> 4. Delete Book
Remove a book from the library by ID. All three BST deletion cases (leaf, one child, two children) are handled.

<br> 
<br> 5. Undo Last Deleted Book
<br> Restores the most recently deleted book using a Stack to implement undo functionality (optional feature).

<br> 
<br> 6. Borrow Book
<br> Records a borrowed book into a Linked List, allowing the user to borrow any available book by ID.

<br> 
<br> 7. Return Book
<br> Marks a borrowed book as returned instead of removing it, maintaining a complete borrowing history.

<br> 
<br> 8. View Borrowed Books
<br> Displays all books ever borrowed with their Borrowed/Returned status — avoiding duplicates and preserving history

# Concepts Used
<br> 
<br> Programming Language: C (Standard C99)
<br> 
<br> Data Structures Used:
<br> 1. Binary Search Tree (for Book Database)
<br> 2. Singly Linked List (for Borrowed Books)
<br> 3. Stack (for Undo functionality)
<br> 

# Algorithms

<br> Insertion, Deletion, In-order Traversal in BST
<br> Linked List insertion, status tracking
<br> Stack push/pop for undo feature


<br> CLI-based Interface with dynamic memory management (malloc, free)


