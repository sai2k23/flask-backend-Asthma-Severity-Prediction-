# Flask Backend - Asthma Severity Prediction

## Overview
This **Flask-based backend** is responsible for processing data and predicting asthma severity based on machine learning models. It provides a REST API for seamless communication with the frontend.

## Features
- REST API endpoints for asthma severity prediction.
- Machine learning model integration for accurate analysis.
- Data validation and error handling.
- Lightweight and scalable architecture.

## Tech Stack
- **Python** - Primary programming language.
- **Flask** - Web framework for API development.
- **Scikit-learn/Pandas** - Machine learning model handling.
- **SQLite/PostgreSQL** - Database support (if applicable).
- flask-backend-Asthma-Severity-Prediction/
│── catboost_info/
│   ├── learn/
│   │   ├── events.out.tfevents
│   │   ├── catboost_training.json
│   │   ├── learn_error.tsv
│   │   ├── time_left.tsv
│   ├── README.md
│── app.py
│── asthma_dataset.csv
│── model.pkl
│── requirements.txt


## Installation
```bash
# Clone the repository
git clone https://github.com/sai2k23/flask-backend-Asthma-Severity-Prediction.git

# Navigate to the project folder
cd flask-backend-Asthma-Severity-Prediction

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Run the Flask application
python app.py
```


## Usage
1. Ensure dependencies are installed.
2. Start the server using `python app.py`.
3. API will be available at `http://localhost:5000`.

## Contribution
Feel free to contribute by submitting issues or pull requests.

## License
This project is licensed under the MIT License.

