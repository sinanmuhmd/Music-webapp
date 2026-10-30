# 🎵 Music Player Web Application

A web-based music player built with **Python, Django, HTML, CSS, and JavaScript**. The project aims to provide a simple and modern interface for discovering music, exploring categories, and enjoying a personalized music experience.

## 📌 About the Project

This project is a music streaming-style web application developed using Django. It uses Django models to manage songs and music categories and dynamically displays content from the database.

The goal is to create a clean, user-friendly music platform with a modern interface and useful music discovery features.

## ✨ Features

* 🎵 **Music Library** — Organize and display songs.
* 📂 **Music Categories** — Browse music by category.
* 🔥 **Popular Songs** — Display songs marked as popular.
* 🖼️ **Dynamic Content** — Retrieve music information from the Django database.
* 👤 **Profile Page** — A dedicated page for the user profile interface.
* 🎨 **Custom User Interface** — A modern web design built with HTML and CSS.
* ⚙️ **Django Backend** — Manage application logic, database queries, and page rendering.

> Note: Features that are still under development may not be fully functional yet.

## 🛠️ Technologies Used

| Technology   | Purpose                                   |
| ------------ | ----------------------------------------- |
| Python       | Backend programming                       |
| Django       | Web framework                             |
| HTML5        | Page structure                            |
| CSS3         | Styling and responsive design             |
| JavaScript   | Frontend interactions                     |
| SQLite       | Database (Django default, if not changed) |
| Git & GitHub | Version control and project hosting       |

## 📁 Project Structure

The project structure may look similar to the following:

```text
music-player/
│
├── manage.py
├── db.sqlite3
│
├── musicapp/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── admin.py
│   └── ...
│
├── templates/
│   ├── home.html
│   └── profile.html
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── media/
│   ├── songs/
│   └── categories/
│
├── requirements.txt
└── README.md
```

*This is an example structure. Adjust the folder and application names to match your actual project.*

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### 2. Navigate to the Project Directory

```bash
cd music-player
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows (PowerShell):**

```powershell
.\venv\Scripts\Activate.ps1
```

**Windows (Command Prompt):**

```cmd
venv\Scripts\activate.bat
```

### 5. Install Dependencies

If the project contains a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

Otherwise, install Django:

```bash
pip install django
```

### 6. Apply Database Migrations

```bash
python manage.py migrate
```

### 7. Create a Superuser (Optional)

To access the Django administration panel:

```bash
python manage.py createsuperuser
```

Follow the prompts to create your administrator account.

### 8. Run the Development Server

```bash
python manage.py runserver
```

Open the following address in your browser:

```text
http://127.0.0.1:8000/
```

## 🗄️ Database Models

The project currently uses the following Django models:

### Song

The `Song` model represents individual songs in the music library.

It can store information such as:

* Song title and details.
* Music category.
* Popularity status.
* Audio file and other metadata, depending on the model definition.

### MusicCategory

The `MusicCategory` model organizes songs into different music categories.

It can store information such as:

* Category name.
* Category image.
* Related songs.

The relationship between songs and categories helps organize the music library and retrieve related content efficiently.

## 🔮 Future Improvements

Planned improvements for the project include:

* [ ] Implement complete music playback controls.
* [ ] Add play, pause, next, and previous song functionality.
* [ ] Create a music search feature.
* [ ] Add user registration and authentication.
* [ ] Implement personalized playlists.
* [ ] Allow users to mark songs as favourites.
* [ ] Complete the user profile page.
* [ ] Improve mobile responsiveness.
* [ ] Add song duration and playback progress controls.
* [ ] Deploy the application online.

## 🎯 Project Goals

The main goals of this project are to:

* Improve Django web development skills.
* Understand Django models, views, templates, and URL routing.
* Learn how to retrieve and display database content dynamically.
* Practice frontend development with HTML, CSS, and JavaScript.
* Build a practical project for a software development portfolio.

## 👨‍💻 Developer

**Sinan**

BCA Student | Aspiring Software Developer

Interested in web development, Python, Django, and building useful applications.

## 📄 License

This project is intended for educational and personal development purposes.

A formal open-source license can be added if the project is published for reuse by others.
