# Backend Bookshop Webpage (MongoDB)

This is a small backend bookshop webpage built using Node.js, EJS view engine, and MongoDB database. The webpage allows you to perform various operations such as adding a book, deleting a book, editing book details, and viewing all the books in the inventory.

['alt text'](./online-shop.png)

## Prerequisites

Before running the application, make sure you have the following installed on your system:

- Node.js: [Download Node.js](https://nodejs.org)
- MongoDB: [Download MongoDB](https://www.mongodb.com/try/download/community)

## Getting Started

1. Clone the repository to your local machine.

```bash
git clone <repository-url>
```

2. Install the dependencies.

```bash
cd backend-bookshop-webpage
npm install
```

3. Start MongoDB:

Make sure MongoDB is running on your system. If you installed MongoDB using the default settings, you should be able to start it by running the `mongod` command in your terminal.

4. Set up Environment Variables:

   - Create a new file named `.env` in the root of the project.
   - Add the following environment variables in the `.env` file:

```env
MONGODB_URI=mongodb://localhost:27017/bookshop
```

Replace `mongodb://localhost:27017/bookshop` with the connection URI for your MongoDB database. The URI should include the host, port, and the name of the database you want to use.

5. Start the application.

```bash
npm start
```

6. Open your web browser and visit `http://localhost:3000` to access the backend bookshop webpage.

## Features

- **Add a Book:** You can add a new book to the inventory by providing book details such as title, author, genre, and quantity.

- **Delete a Book:** If a book is no longer available, you can easily delete it from the inventory.

- **Edit Book Details:** If any book details need to be updated, you can edit the book's information like title, author, genre, and quantity.

- **View All Books:** The webpage allows you to view all the books currently available in the bookshop's inventory.

## Technologies Used

- Node.js: JavaScript runtime for server-side development.
- EJS View Engine: Embedded JavaScript templates for rendering dynamic content.
- MongoDB: NoSQL database for data storage.
