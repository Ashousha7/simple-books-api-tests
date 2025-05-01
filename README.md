# simple-books-api-tests
🔬 Hands-on API Testing project using Postman based on Simple Books API. Covers real-world scenarios like registration, listing, ordering, and validation.

# 🧪 API Testing Project – Simple Books API

This is a hands-on API testing project built using **Postman**, based on the public [Simple Books API](https://simple-books-api.glitch.me).  
The goal is to simulate real-world scenarios such as user registration, listing books, placing orders, and testing API responses using assertions.

---

## 📁 Project Contents

- ✅ Test Cases for:
  - API Status Check
  - User Registration
  - Listing Books (with filters)
  - Get Single Book by ID
  - Place Book Orders
  - Get, Update, and Delete Orders
- 🧪 Postman test scripts
- 🌐 Usage of environment variables (`baseURL`, `accessToken`, `bookID`, `orderID`)
- 📋 Test result assertions (status codes, response body validation)

---

## 🧰 Tools Used

- [Postman](https://www.postman.com/)
- JavaScript Test Scripts (for response validation)
- Environment Variables
- (Optional) Excel / Markdown for reporting

---

## 📌 How to Use

1. Clone or download this repository.
2. Import the `API Course.postman_collection.json` into Postman.
3. Set the `baseURL` to: https://simple-books-api.glitch.me
4. Register a client to get `accessToken`.
5. Set environment variable `accessToken` to access protected endpoints.
6. Run requests step-by-step or in sequence.

---

## ✅ Example Test Scenarios

| # | Name | Method | Description |
|---|------|--------|-------------|
| 1 | API Status | GET | Check if API is up |
| 2 | Register API Client | POST | Register new API user |
| 3 | List of Books | GET | Get available books by type |
| 4 | Get a Book | GET | Retrieve a specific book |
| 5 | Order Book | POST | Place a new order |
| 6 | Get All Orders | GET | View all placed orders |
| 7 | Get Single Order | GET | View details of an order |
| 8 | Update Order | PATCH | Update customer's name |
| 9 | Delete Order | DELETE | Cancel an order |

---

## 🧠 What I Learned

- REST API structure and behavior
- Writing and running test assertions
- Managing environments and chaining requests
- Negative testing (handling error scenarios)
- Real-world testing workflow in Postman
