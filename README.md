🛡️ Phishing URL Detection using Machine Learning

A Machine Learning-based web application that detects phishing (malicious) URLs by analyzing multiple lexical and domain-based features.
The project combines Flask, Python, and ML algorithms to provide real-time predictions through a simple and interactive web interface.

🚀 Features

🧠 Machine Learning Model: Trained on a labeled dataset of phishing and legitimate URLs.

🔗 Feature Extraction: Extracts 30+ features (length, dots, prefixes, SSL status, etc.).

🌐 Web App (Flask): Interactive user interface to test URLs instantly.

📊 Accurate Prediction: Uses Scikit-learn classifiers (Random Forest / Logistic Regression).

🎨 Responsive UI: Styled with HTML, CSS for a user-friendly experience.

🧩 Tech Stack
Category	Technologies
Programming Language	Python
Libraries / Frameworks	Flask, Scikit-learn, Pandas, NumPy, Joblib
Frontend	HTML, CSS
Development Tools	Jupyter Notebook, VS Code
Version Control	Git & GitHub
🗂️ Project Structure
Phishing-URL-Detection/
│
├── app.py                   # Flask web application
├── feature.py               # Feature extraction logic
├── Phishing URL Detection.ipynb  # Model training notebook
├── requirements.txt          # Dependencies
├── README.md                 # Project documentation
├── static/
│   └── styles.css            # Frontend styles
├── templates/
│   └── index.html            # Web interface
└── pickle/
    └── model.pkl             # Trained model file

⚙️ Installation & Setup
🖥️ Prerequisites

Ensure you have the following installed:

Python 3.8 or above

pip (Python package manager)

📦 Steps
# 1. Clone the repository
git clone https://github.com/<your-username>/Phishing-URL-Detection.git
cd Phishing-URL-Detection

# 2. (Optional) Create virtual environment
python -m venv venv
venv\Scripts\activate   # for Windows
# or
source venv/bin/activate  # for Mac/Linux

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Flask app
python app.py


Then open your browser and go to:
👉 http://127.0.0.1:5000/

📊 Model Training

The model was trained using Phishing URL Detection.ipynb.
It extracts lexical and domain-based features, then applies ML algorithms such as:

Random Forest Classifier

Decision Tree

Logistic Regression

To retrain:

Open the Jupyter Notebook.

Run all cells.

The trained model is saved as pickle/model.pkl.

🧠 How It Works

The user enters a website URL.

The system extracts important features (like URL length, presence of “@”, subdomain count, etc.).

The ML model predicts whether the URL is Phishing or Legitimate.

The result is displayed instantly on the web interface.

⚠️ Note

The trained model (model.pkl) may not be included due to GitHub file size limits.
You can retrain it using the notebook or download from the release section.

🏆 Project Outcomes

Achieved high accuracy in phishing detection.

Demonstrated integration of Machine Learning + Web Development.

Useful as a cybersecurity tool for identifying suspicious URLs.
