![todolist](https://github.com/user-attachments/assets/c4986773-35d9-4e70-b63d-ff87c08adc29)

### **Project Overview**

**Tech Stack:**

-   **Node.js** (Server-side)
-   **Express.js** (Routing)
-   **EJS** (Templating)
-   **PostgreSQL** (Database)
-   **HTML/CSS** (Frontend)

----------

### **Features of the Permalist Project**

1.  **Add a List**: Users can add new items to the list.
2.  **Delete a List**: Users can remove specific items.
3.   **Edit a list**: Edit your items to the list.
4.  **View All Lists**: Users can see all the items in the list.

----------

### **Folder Structure**

```
Permalist/
│
├── app.js                 # Main server file
├── public/                # Static files (CSS/JS)
│   └── styles.css         # Basic styles for the app
├── views/                 # EJS templates
│   ├── index.ejs          # Main page
│   ├── layout.ejs         # Layout for reusability
│   └── partials/          # Partial components (header/footer)
├── README.md              # Project README file
└── package.json           # Project dependencies

```

----------

### **README Template**

```markdown
# Permalist Project

## 📋 Overview
Permalist is a Node.js application that lets users create, view, and delete items from a list. It uses PostgreSQL for database management and EJS for templating.

---

## 🛠️ Features
- Add items to the list
- Edit your items to the list
- View all items
- Delete items from the list

---

## 📚 Tech Stack
- **Backend**: Node.js, Express.js.
- **Frontend**: HTML, CSS, EJS.
- **Database**: PostgreSQL.

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/sheftectdad/permalist.git
   cd permalist

```

2.  Install dependencies:
    
    ```bash
    npm install
    
    ```
    
3.  Set up the database:
    
    -   Create a PostgreSQL database.
    -   Run the SQL script in `db/database.sql` to create the necessary tables.
4.  Start the server:
    
    ```bash
    node index.js
    
    ```
    
5.  Open the app in your browser:
    
    ```
    http://localhost:3000
    
    ```
----------   

## 🛑 Prerequisites

-   **Node.js** installed
-   **PostgreSQL** set up on your system

----------

## 📄 Database Schema

```sql
CREATE TABLE items (
    id SERIAL PRIMARY KEY,
    title TEXT NOT NULL
);

```

----------

## 💻 APIs

Method

Endpoint

Description

GET

`/`

View all list items

POST

`/add`

Add a new list item

POST

Edit the list.

POST

`/delete

Delete a list item

----------

## 🧑‍💻 Contribution

Feel free to submit issues or pull requests.

----------

## 📜 License

This project is licensed under the MIT License.

```


