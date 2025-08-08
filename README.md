
#  ToDo WebApp (FastAPI)

This is a simple yet functional ToDo Web Application built with **FastAPI**, **SQLite**, and **Jinja2 templates**. It allows users to manage tasks (CRUD), authenticate using JWT tokens, and supports admin roles and user registration.

---

##  Features

-  User registration & login (JWT-based)
-  Admin panel with user management
-  Create, Read, Update, Delete ToDos
-  Priority-based task sorting
-  SQLAlchemy ORM + SQLite database
-  Jinja2 templating (HTML/CSS)
- 🗃 Organized folder structure (routers, models, templates, static)

---

##  Project Structure

```

ToDoApp/
├── main.py                 # FastAPI app entry point
├── database.py             # DB engine and session
├── models.py               # SQLAlchemy models
├── routers/                # Route logic
│   ├── auth.py             # Login, registration
│   ├── todos.py            # ToDo CRUD
│   ├── admin.py            # Admin routes
│   └── users.py            # User profile routes
├── templates/              # HTML pages
├── static/                 # CSS, images
└── README.md

````

---

##  Installation

1. **Clone the repo**

```bash
git clone https://github.com/KerimKarovic/ToDo-WebApp.git
cd ToDo-WebApp
````

2. **Create a virtual environment**

```bash
python -m venv .venv
.venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the app**

```bash
uvicorn main:app --reload
```

Open your browser: [http://127.0.0.1:8000](http://127.0.0.1:8000)
Docs: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

---

##  API Docs

Powered by FastAPI:

* Swagger UI: `/docs`
* ReDoc: `/redoc`

---

##  License

MIT License. Free to use and modify.

---

##  Author

Made by **Kerim Karovic** – [GitHub](https://github.com/KerimKarovic)

```

---

###  Next Steps (Optional)
If you want, I can also:
- Generate a `requirements.txt`
- Create `.gitignore`
- Add environment variable support (`.env`)
- Add JWT helper module

Let me know and I’ll generate them instantly.
```
