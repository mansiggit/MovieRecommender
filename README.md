# MovieRecommenderUsingDjango

A content-based movie recommendation engine built on the Django framework. This project demonstrates full-stack web development combined with data processing and a core machine learning technique (similarity scoring) to provide personalized movie suggestions.

## Key Features

* **Personalized Recommendation Engine:** Implements a custom content-based filtering algorithm that analyzes the genre tags of a user's "watched" movies to recommend similar "unwatched" movies.
* **Genre Similarity Scoring:** Utilizes the **Jaccard Similarity Coefficient** to quantitatively measure the overlap between movie genre sets, ensuring recommendations are highly relevant.
* **Django Management Command:** Recommendation generation is executed via a `make_recommendations` custom management command, allowing for efficient, periodic updating of the recommendation dataset.
* **Responsive User Interface:** Presents the recommendation list on a clean, responsive front-end built using **Django Templates** and styled with **Bootstrap 4** for optimal viewing on desktop and mobile.
* **Optimized Data Handling:** Leverages the **Django ORM** to efficiently query, filter, and update large datasets of movies based on `watched` and `recommended` flags.

## Technologies Used

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Backend Framework** | **Django** | Main web framework (Python) |
| **Programming Language** | **Python 3** | Core language for business logic and similarity functions |
| **Database** | **Django ORM** (Model) | Data modeling and efficient database query abstraction |
| **Algorithm** | **Jaccard Similarity** | Core technique for calculating genre-based movie similarity |
| **Frontend/Templating** | **Django Templates (HTML/CSS)** | Dynamic page rendering and data presentation |
| **Styling** | **Bootstrap 4** | Responsive design and component styling |
