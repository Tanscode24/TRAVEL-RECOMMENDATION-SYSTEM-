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
TRAVEL_BUDDY/
├── app/
│   ├── __init__.py             # Initialize Flask app
│   ├── routes.py               # URL routes and views
│   ├── recommender.py          # Recommendation logic using ML
│   ├── utils.py                # Helper functions (e.g., search, filters)
│   ├── templates/
│   │   └── index.html          # Frontend UI using Jinja2
│   └── static/
│       ├── css/
│       ├── js/
│       └── images/
│
├── data/
│   └── tourist_places.jsonl    # Dataset
│
├── models/
│   └── model.pkl               # ML model
│
├── requirements.txt            # Python dependencies
├── run.py                      # Entry point to run Flask app
└── README.md
