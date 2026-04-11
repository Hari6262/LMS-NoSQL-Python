# Library Management System (NoSQL)

A Python-based Library Management System developed for the **S4 CSE DBMS Mini Project**. This system implements core library workflows using **MongoDB**, demonstrating the application of NoSQL principles to a traditionally relational problem.

## 🚀 Key Features
* **Dynamic Inventory:** Real-time tracking of book availability and stock counts.
* **Member Portal:** Efficient registration and management of library patrons.
* **Automated Transactions:** Atomic-style issue and return workflows that ensure data consistency across collections.
* **Audit Trail:** A permanent `transactions` collection recording every event with ISO-standard timestamps.

## 📊 Data Architecture
The system is built on a non-relational schema designed for high-performance lookups:

| Collection | Role | Key Data Points |
| :--- | :--- | :--- |
| `books` | Inventory | Title, Author, CategoryID, Stock |
| `members` | Registry | MemberID, Contact Info, Active Loans |
| `issued_books` | Active State | BookID, MemberID, Due Date |
| `transactions` | History | Action (Issue/Return), Timestamp |

## 🛠️ Tech Stack
* **Backend:** Python 3.x
* **Database:** MongoDB (NoSQL)
* **Library:** `pymongo`

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Hari6262/LMS-NoSQL-Python](https://github.com/Hari6262/LMS-NoSQL-Python)# Library Management System (NoSQL)

A Python-based Library Management System using **MongoDB** as the backend database. This project was developed as part of the S4 DBMS Mini Project curriculum.

## 🚀 Features
* **Book Management:** Add, view, and categorize books with real-time stock tracking.
* **Member Management:** Register and maintain library member records.
* **Transaction Logic:** Automated issue and return workflows that update book availability.
* **Category Mapping:** Relational-style linking between categories and books within a NoSQL environment.
* **Audit Log:** A dedicated transactions collection to track every issue and return event with timestamps.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Database:** MongoDB (NoSQL)
* **Driver:** `pymongo`

## 📊 Database Schema
The system utilizes five collections within the `library_dbteat` database:
1.  `books`: Stores title, author, category mapping, and stock count.
2.  `members`: Stores member IDs and contact information.
3.  `issued_books`: Tracks currently active loans.
4.  `categories`: Stores distinct book genres/categories.
5.  `transactions`: A permanent history of all library activities.

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   https://github.com/Hari6262/LMS-NoSQL-Python
