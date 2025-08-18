# 🎬 My Top Movies


🚀 **Try it out here → [my-top-movies-cf1r.onrender.com](https://my-top-movies-cf1r.onrender.com)**  


**My Top Movies** is a full-stack Flask web application that lets users search for films via the [TMDB API](https://www.themoviedb.org/), crate a personalized top movie list, and manage reviews and ratings in a clean and responsive UI.

Deployed with [Render](https://render.com/), this project also features user authentication, API integration, dark mode styling, and custom UI animations.

[![Built with Flask](https://img.shields.io/badge/Built%20With-Flask-orange)](https://flask.palletsprojects.com/) [![TMDB API](https://img.shields.io/badge/API-TMDB-brightgreen)](https://www.themoviedb.org/documentation/api)

---

## 🌟 Features

- 🔐 **User Registration & Login** – Secure authentication system with password hashing.
- 🔍 **Movie Search** – Find movies using the TMDB API and select them from search results.
- ⭐ **Rate & Review** – Assign a score out of 10 and leave a custom review.
- 📋 **Top Movies** – Manage your personalized list, sorted by rating.
- 🖊️ **Edit & Delete** – Modify your ratings or remove a movie anytime.
- 🧠 **Smart Duplicate Check** – Prevent adding the same movie twice.
- 🎨 **Responsive UI** – Fully optimized for desktop, tablet, and mobile with Bootstrap 5 and custom dark theme.
- 🍿 **Interactive Effects** – Custom JavaScript animations (like popcorn burst 🎉).
- 🧪 **API-Driven Content** – Live trending and Oscar-predicted movies from TMDB.
- 🌍 **Deployed on Render** – With a `/ping` route for UptimeRobot integration.

---

## 🖼️ Screenshots  
*Click any image to view it in full size.*


|     🏠 Home Page (Not Logged In) |            🏆 Oscar & Trending Movies |
|----------------------------------------|---------------------------------------|
| ![Home Page](https://github.com/user-attachments/assets/5497b2d7-1df2-47d9-934f-aa483ff9156f) | ![Oscar](https://github.com/user-attachments/assets/380585fa-fc90-41ff-8fae-83a7bb20fda5) |


| 🔍 Search & Add Movies       | ✅ Add to Top              |
|-----------------------------|----------------------------|
| ![Search](https://github.com/user-attachments/assets/8ddc36fa-c1e9-42fb-bb39-38ad112f79b9) | ![Add to Top](https://github.com/user-attachments/assets/bc1426b5-e6c3-40fe-b369-97cad8cc2053) |

| 🎞️ Your Top Movies (List View) | 🧾 Edit Rating         |
|--------------------------------|------------------------|
| ![Top Movies](https://github.com/user-attachments/assets/bf6aa512-f047-46a2-98ae-5c389874dae7) | ![Edit Rating](https://github.com/user-attachments/assets/ec04b0c0-337a-4cba-892a-e24d955fcc55) |

---
## 🎥 Demo Video

Want to see it in action? This demo shows some of the features this site has:

📺 [Watch the demo on YouTube](https://www.youtube.com/watch?v=Ff19muasS8A)

### 🧪 Features demonstrated:
- 🧾 Creating an account
- 🔎 Searching for movies via TMDB API
- 🎞️ Adding movies from both *search* and *trending/Oscar* sections
- ✏️ Editing ratings and reviews
- 🗑️ Deleting movies from your top list
- 🧩 Dynamic sorting view: toggle between *list* and *grid* layouts with smooth animations
- 🚪 Logging out
- 🔐 Testing restricted access when logged out (add/top page)

> 💡 *Click the link to open the video in full screen.*

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.x  
- `pip` or `venv`  
- TMDB API Key (get one [here](https://www.themoviedb.org/documentation/api))  
- Set the following **environment variables** in your IDE or deployment platform:

```bash
FLASK_SECRET_KEY=your-secret-key
TMDB_API_KEY=your-tmdb-key
```

> 💡 In local development, you can add these in your IDE's run configuration (e.g., PyCharm > Run/Debug Configurations > Environment Variables).


---

### 🛠 Installation

```bash
git clone https://github.com/RuginaAlex/my-top-movies.git
cd my-top-movies
pip install -r requirements.txt
python main.py
```

Visit `http://127.0.0.1:8081` in your browser.

---



## ⚙️ Tech Stack

| Tech        | Purpose                           |
|-------------|------------------------------------|
| Flask       | Backend web framework              |
| Flask-Login | User authentication                |
| SQLite      | Lightweight database               |
| Bootstrap 5 | Frontend styling                   |
| Jinja2      | HTML templates with logic          |
| TMDB API    | Fetching movie data                |
| Render      | Free cloud deployment              |
| UptimeRobot | Keep-alive pinging for free tier   |

---

## 🤝 Contributions

This project is a personal educational app built to showcase full-stack Python + Flask skills.

If you’d like to contribute, open a pull request or reach out via:


---

## 🔗 Credits

Movie data provided by [TMDB API](https://www.themoviedb.org/documentation/api)  
Icons by [Bootstrap Icons](https://icons.getbootstrap.com/)  
Project built by **Mocan Bogdan Anton Eliazar**
