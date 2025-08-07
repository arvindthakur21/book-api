# 📚 Book List REST API

This is a simple **RESTful API** built using **Node.js** and **Express** to manage a list of books. It supports full **CRUD operations** and stores book data **in memory** (no database).

---

## 🚀 Features

- 📖 Get all books
- ➕ Add a new book
- ✏️ Update a book by ID
- ❌ Delete a book by ID

---

## 🛠️ Tech Stack

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Postman](https://www.postman.com/) – for testing

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/arvindthakur21/book-api.git
cd book-api
Install dependencies:

npm install
Run the server:


node index.js
The server will start at:
📍 http://localhost:3000
📁 Sample Data Structure
json
Copy
Edit
{
  "id": 1,
  "title": "The Alchemist",
  "author": "Paulo Coelho"
}
📬 API Endpoints
➤ Get All Books
bash
Copy
Edit
GET /books
Returns a list of all books.

➤ Add New Book
bash
Copy
Edit
POST /books
Body (JSON):

json
Copy
Edit
{
  "title": "Rich Dad Poor Dad",
  "author": "Robert Kiyosaki"
}
➤ Update Book by ID
bash
Copy
Edit
PUT /books/:id
Example: /books/1
Body (JSON):

json
Copy
Edit
{
  "title": "Updated Title",
  "author": "Updated Author"
}
➤ Delete Book by ID
bash
Copy
Edit
DELETE /books/:id
Example: /books/1

🧪 Testing with Postman
Install Postman

Send requests to:
http://localhost:3000/books

⚠️ Note
This API uses in-memory storage, so all data will reset when the server restarts. Ideal for learning and testing purposes.

🙌 Author
Made with 💻 by Arvind Thakur
🔗 LinkedIn
🐙 GitHub
