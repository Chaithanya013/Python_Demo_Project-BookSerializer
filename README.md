## 📘 BookSerializer API

A simple and clean **Django REST Framework (DRF)** project that demonstrates how to build, serialize, and expose a RESTful API for managing books.  
It allows you to **create, view, update, and delete** book records easily through an API endpoint.

---

### 🚀 Features

- 📚 CRUD operations for books (Create, Read, Update, Delete)  
- ⚙️ Built with **Django** and **Django REST Framework**  
- 🔄 JSON-based API responses  
- 🧩 Admin panel for managing books visually  
- 💡 Beginner-friendly and easy to extend  

---

### 🏗️ Project Structure

```
BookSerializer/
├── books/
│   ├── admin.py
│   ├── models.py
│   ├── serializers.py
│   ├── urls.py
│   └── views.py
├── mysite/
│   ├── settings.py
│   ├── urls.py
├── manage.py
└── README.md
```

---

### ⚙️ Installation Guide

#### 1️⃣ Clone the repository
```bash
git clone https://github.com/Chaithanya013/Book-Serializer-Project.git
cd BookSerializerAPI
```

#### 2️⃣ Create and activate a virtual environment
```bash
python -m venv venv
venv\Scripts\activate   # for Windows
# or
source venv/bin/activate   # for Mac/Linux
```

#### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

#### 4️⃣ Run migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

#### 5️⃣ Create an admin user
```bash
python manage.py createsuperuser
```

#### 6️⃣ Start the server
```bash
python manage.py runserver
```

Then open your browser at:
```
http://127.0.0.1:8000/api/books/
```

---

### 🌐 API Endpoints

| Method | Endpoint | Description |
|--------|-----------|-------------|
| GET | `/api/books/book` | List all books |
| POST | `/api/books/book/add` | Add a new book |
| PUT | `/api/books/{id}/change/` | Update a book |
| DELETE | `/api/books/{id}/change/` | Delete a book |

---
### Outputs of the Project

1. Run Server

![backup](https://github.com/Chaithanya013/Python_Demo_Project-BookSerializer/blob/5d2081be1dfb974d52c52c537b268ef159631820/outputs_screenshots/run_server.png)


2. Admin Page

![backup](https://github.com/Chaithanya013/Python_Demo_Project-BookSerializer/blob/5d2081be1dfb974d52c52c537b268ef159631820/outputs_screenshots/admin_page.png)


3. List All Books

![backup](https://github.com/Chaithanya013/Python_Demo_Project-BookSerializer/blob/5d2081be1dfb974d52c52c537b268ef159631820/outputs_screenshots/list_of_books.png)


4. Add a New Book

![backup](https://github.com/Chaithanya013/Python_Demo_Project-BookSerializer/blob/5d2081be1dfb974d52c52c537b268ef159631820/outputs_screenshots/adding_book.png)


5. Update a Single Book

![backup](https://github.com/Chaithanya013/Python_Demo_Project-BookSerializer/blob/5d2081be1dfb974d52c52c537b268ef159631820/outputs_screenshots/Retrieve_a_single_%20book.png)


6. Delete a Selected Book

![backup](https://github.com/Chaithanya013/Python_Demo_Project-BookSerializer/blob/5d2081be1dfb974d52c52c537b268ef159631820/outputs_screenshots/delete_selected_books.png)

---
### 🧠 Example JSON Data

```json
{
  "title": "Atomic Habits",
  "author": "James Clear",
  "description": "A practical guide to building good habits and breaking bad ones."
}
```

---

### 🧾 Technologies Used

- Python 🐍  
- Django 🌐  
- Django REST Framework ⚙️  
- SQLite 🗃️  

---

### 🧑‍💻 Developer

**Name:** Venuthurla Siva Chaithanya  
**Email:**  chaithanyav.0203@gmail.com
**GitHub:** [@Chaithanya013](https://github.com/Chaithanya013)

---

### 💬 Feedback

If you found this project helpful, please ⭐ star the repository and share your thoughts!

---

### 🏁 Admin Panel Access
Once the server is running, access the admin panel at:

👉 [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

Login using your superuser credentials to add or edit books visually.

---

