# Library Management System (NoSQL)

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
   git clone [https://github.com/your-username/library-mgmt-mongodb.git](https://github.com/your-username/library-mgmt-mongodb.git)
   cd library-mgmt-mongodb
