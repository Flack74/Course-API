# 📚 Course API

A simple REST API for managing courses, built using Go and Gorilla Mux. 🚀

## ✨ Features
- 📖 Get all courses
- 🔍 Fetch a single course by ID
- ➕ Add a new course
- ✏️ Update an existing course
- ❌ Delete a course

## 🛠 Tech Stack
- 🐹 Go (Golang)
- 📦 Gorilla Mux
- 🌐 JSON-based API

## 🚀 Getting Started
### 1️⃣ Clone the repository:
```bash
git clone https://github.com/Flack74/CourseAPI.git
cd CourseAPI
```

### 2️⃣ Install dependencies:
```bash
go mod tidy
```

### 3️⃣ Run the API:
```bash
go run main.go
```

API will be available at: **http://localhost:8000**

## 🔗 API Endpoints
| Method | Endpoint         | Description            |
|--------|----------------|------------------------|
| GET    | `/courses`     | Fetch all courses     |
| GET    | `/course/{id}` | Fetch a course by ID  |
| POST   | `/course`      | Add a new course      |
| PUT    | `/course/{id}` | Update a course       |
| DELETE | `/course/{id}` | Delete a course       |

## 🎯 Example Course JSON
```json
{
  "coursename": "Flask with Flack",
  "price": 199,
  "author": {
    "fullname": "Flack",
    "website": "https://blogzy-1.onrender.com/"
  }
}
```

## 🤝 Contributing
Feel free to fork, open issues, or submit PRs! Contributions are welcome. 😊

## 📜 License
This project is licensed under the MIT License.
