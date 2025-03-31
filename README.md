# Smart Shopping - Personalized E-Commerce Recommendations

## 📌 Project Overview
This project is built for the **Accenture AI Hackathon**, focusing on developing a **Smart Shopping system** that provides **personalized e-commerce recommendations** using AI-driven techniques. The system will leverage multi-agent AI, retrieval-based methods, and recommendation models to enhance user experience.

## 📂 Project Structure
```
.
│   .gitignore
│   config.py               # Configuration settings for the project
│   README.md               # Project documentation
│   requirements.txt        # Dependencies
│
├───agents                 # AI Agents handling various tasks
│       query_agent.py      # Handles user queries
│       recommendation_agent.py  # Manages product recommendations
│       retrieval_agent.py  # Fetches relevant data
│
├───api                    # API implementation for model integration
│       main.py            # FastAPI-based backend
│
├───data                   # Stores datasets
│       customer_data_collection.csv
│       product_recommendation_data.csv
│
├───db                     # Database management
│       database.sqlite    # SQLite database
│       db_utils.py        # Database utility functions
│
├───models                 # Trained recommendation models
│       recommendation_model.pkl
│
├───notebooks              # Jupyter notebooks for model training & experimentation
│
├───tests                  # Unit tests for validation
│
└───utils                  # Utility scripts
        helpers.py         # Common helper functions
```

## 🚀 How We Will Proceed
