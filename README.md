# 🧭 Travel Buddy – Indian Travel Recommendation System 🇮🇳

Welcome to **Travel Buddy**, a smart travel recommendation system built using Python, FastAPI, and Machine Learning. This project recommends top-rated Indian tourist destinations based on user preferences, and provides location-based suggestions with images and key details.

---

## 🚀 Features

- ✅ Personalized travel recommendations
- ✅ Content-based filtering using tourist place descriptions
- ✅ Location, category, and rating filters
- ✅ Real-time image fetching using Google Image Search
- ✅ RESTful API with FastAPI
- ✅ Frontend integration using Jinja templates

---

## 🧠 Tech Stack

| Component        | Technology           |
|------------------|----------------------|
| Backend API      | FastAPI              |
| Data Handling    | Pandas, JSONL        |
| Machine Learning | Scikit-learn, XGBoost|
| Web Templating   | Jinja2               |
| Visualization    | Matplotlib, Seaborn  |
| Deployment       | Vercel (Optional)    |

---

## 📁 Project Structure

| File/Folder                  | Type          | Description                                |
|-----------------------------|---------------|--------------------------------------------|
| `TRAVEL_BUDDY/`             | 📁 Folder     | Root project directory                     |
| ├── `app/`                  | 📁 Folder     | Contains main Flask app files              |
| │   ├── `__init__.py`       | 🐍 Python     | Initialize Flask app                       |
| │   ├── `routes.py`         | 🐍 Python     | URL routes and views                       |
| │   ├── `recommender.py`    | 🐍 Python     | ML recommendation logic                    |
| │   ├── `utils.py`          | 🐍 Python     | Helper functions (search, filters)         |
| │   └── `templates/`        | 📁 Folder     | Jinja2 templates for frontend UI           |
| │       └── `index.html`    | 🖥️ HTML       | Frontend homepage                          |
| │   └── `static/`           | 📁 Folder     | Static assets (CSS, JS, images)            |
| │       ├── `css/`          | 📁 Folder     | Stylesheets                                |
| │       ├── `js/`           | 📁 Folder     | JavaScript files                           |
| │       └── `images/`       | 📁 Folder     | Image assets                               |
| ├── `data/`                 | 📁 Folder     | Dataset storage                            |
| │   └── `tourist_places.json` | 📄 JSON     | Data file with tourist places              |
| ├── `models/`               | 📁 Folder     | ML model directory                         |
| │   └── `model.pkl`         | 📦 Pickle     | Trained ML model file                      |
| ├── `requirements.txt`      | 📄 Text       | Python dependencies                        |
| ├── `run.py`                | 🐍 Python     | Main entry point to run the Flask app      |
| └── `README.md`             | 📄 Markdown   | Project documentation (this file)          |
