# 🎬 MovieRecommender Using Django: Your Personal Cinephile Engine

## Stop Scrolling, Start Watching.

This project delivers a robust, server-side movie recommendation platform built entirely with **Python/Django**. It solves the "what to watch next" dilemma by leveraging **Content-Based Filtering**, providing truly personalized suggestions based on your viewing history.

It's a demonstration of integrating **full-stack web development** (Django MVC) with a core **data science algorithm** (Jaccard Similarity) for practical, real-world utility.

---

## ✨ Features That Drive Personalization

* **🧠 Intelligent Content-Based Filtering:** Dive deeper than simple popularity lists. The system analyzes the *genres* of your **watched** movies to find similar, **unwatched** films, ensuring highly relevant recommendations.
* **📐 The Jaccard Index Core:** We use the powerful **Jaccard Similarity Coefficient** to quantify the genre overlap between any two movies (e.g., comparing sets of genres). A higher Jaccard score guarantees a closer match to your taste profile.
* **🚀 Optimized Recommendation Pipeline:** Recommendation generation is executed offline via a custom **Django Management Command** (`python manage.py make_recommendations`), ensuring the main web application remains fast and responsive.
* **🖥️ Responsive & Sleek UI:** The front-end is rendered dynamically using **Django Templates** and styled with **Bootstrap 4**, guaranteeing an intuitive and beautiful experience across all devices.
* **⚡ Efficient Data Layer:** Leverages the **Django ORM** for high-performance, complex database queries, efficiently handling large datasets of movie records and their associated flags (`watched`, `recommended`).

---

## ⚙️ The Technology Stack

| Category | Technology | Focus/Role modeling and efficient database query abstraction |
| **Algorithm** | **Jaccard Similarity** | Core technique for calculating genre-based movie similarity |
| **Frontend/Templating** | **Django Templates (HTML/CSS)** | Dynamic page rendering and data presentation |
| **Styling** | **Bootstrap 4** | Responsive design and component styling |
