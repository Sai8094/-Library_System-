# 📚 Library System in Java

## 📌 Overview
This project simulates a **Library Management System** in Java.  
It demonstrates **Classes, Methods, State Management, and Constructors** using only arrays.  
The system allows issuing, returning, and listing books from a small library.

---

## 🛠 Features
- Maximum **5 books** stored in the library.
- Each book has:
  - 📖 **Title**  
  - ✍️ **Author**  
  - 🔒 **Issued Status** (issued / available)  
- Operations available:
  - ✅ **Issue a Book**  
  - 🔄 **Return a Book**  
  - 📑 **List Available Books**  

---

## 🏗 Design
- **Book (Class)**  
  - Fields: `title`, `author`, `isIssued`  
  - Methods: `issueBook()`, `returnBook()`, `isAvailable()`  
- **Library (Class)**  
  - Holds an array of max **5 books**  
  - Methods: `addBook()`, `issueBook()`, `returnBook()`, `listAvailableBooks()`  
- **Main (Simulation Class)**  
  - Provides a menu to manage the library system  

---

## 🎯 Core Logic
- When a book is **issued**, its `isIssued` flag is set to `true`.  
- When a book is **returned**, the flag is reset to `false`.  
- **List Available Books** shows only books where `isIssued == false`.  

---

## 📚 OOP Concepts Used
- **Classes & Objects** → Defined `Book`, `Library`, and `Main`.  
- **Methods** → For book operations like issue, return, and list.  
- **State Management** → Maintains whether a book is issued or available.  
- **Constructors** → Initialize book details (title, author, issued status).  
