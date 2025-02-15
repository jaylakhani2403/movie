# Machine Learning-Based Recommendation System

## Overview
This project implements a **machine learning-based recommendation system** using **vectorization** techniques. The system processes data and generates recommendations using similarity measures stored in `similarity.pkl`.

## Features
- **Content-Based Filtering** using vectorization
- **Pre-trained Model** stored in `similarity.pkl`
- **Movie/Data Recommendations**
- **Deployment Ready** with `procfile` and `setup.sh`
- **Live Demo**: [Indian Movie Recommendation](https://indian-movie-recommendation.onrender.com/)

## Tech Stack
- **Programming Language**: Python
- **Machine Learning**: Scikit-learn, Pandas, NumPy
- **Storage**: Pickle for model storage (`similarity.pkl`, `movie_dict.pkl`)
- **Deployment**: Render

## Installation Steps
### 1. Clone the Repository
```sh
git clone https://github.com/jaylakhani2403/movie-recommendation
cd movie-recommendation
```

### 2. Install Dependencies
```sh
pip install -r requirements.txt
```

### 3. Run the Application
```sh
python app.py
```

### 4. Deployment
- Use `procfile` for Heroku deployment.
- Execute `setup.sh` for environment setup.
- Live version hosted on Render: [Indian Movie Recommendation](https://indian-movie-recommendation.onrender.com/)

## Folder Structure
```
/project-directory
│── app.py             # Main Application File
│── similarity.pkl     # Pre-trained Similarity Model
│── movie_dict.pkl     # Movie/Data Dictionary
│── requirements.txt   # Dependencies
│── procfile           # Deployment Configuration
│── setup.sh           # Setup Script
│── .gitignore         # Git Ignore Rules
│── .gitattributes     # Git Attributes
│── README.md          # Project Documentation
```

## Future Enhancements
- Improve recommendation accuracy
- Add user-based collaborative filtering
- Deploy as a web service

## License
This project is open-source and free to use.

---
Made with ❤️ by **jay lakhani**


