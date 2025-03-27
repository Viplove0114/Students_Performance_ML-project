# 🎓 Students Performance ML Project

## 📝 **Project Description**
This project predicts **students' performance** based on various factors using **Machine Learning models**. It includes **Exploratory Data Analysis (EDA)**, model training, and a web-based interface for making predictions. The project is built with **Python**, **CatBoost**, and **Flask**.

---

## 🚀 **Features**
- **Exploratory Data Analysis (EDA):** Analyze patterns and trends in student performance data.
- **Model Training:** Train ML models using CatBoost and evaluate performance.
- **Prediction Pipeline:** Make predictions using a web-based interface.
- **Logging & Exception Handling:** Integrated logs and exception handling for debugging.
- **Web Application:** Built with Flask and HTML templates.

---

## 🔥 **Project Structure**
```
Students_Performance_ML-project-main/
├── Notebook/                     # Jupyter notebooks for EDA and model training
│   ├── EDA STUDENT PERFORMANCE.ipynb   # Exploratory Data Analysis notebook
│   ├── MODEL TRAINING.ipynb           # Model training steps
│   ├── Data/
│       └── stud.csv                   # Dataset for training
├── artifacts/                     # Model artifacts and preprocessed data
│   ├── model.pkl                   # Trained model
│   ├── preprocessor.pkl            # Preprocessing pipeline
│   ├── train.csv / test.csv        # Train/test datasets
├── logs/                          # Logs generated during execution
├── src/                           # Source code for the ML pipeline
│   ├── components/                 # Data ingestion, transformation, and model trainer scripts
│   ├── pipeline/                   # Training and prediction pipelines
│   ├── exception.py                # Custom exceptions
│   ├── logger.py                   # Logging utility
│   └── utils.py                    # Utility functions
├── templates/                      # HTML templates for web UI
│   ├── home.html                   # Home page template
│   ├── index.html                  # Main page template
├── application.py                  # Main application script for running the web app
├── Setup.py                        # Setup configuration
├── requirements.txt                # Dependencies
├── .gitignore                      # Git ignore file
└── .ebextensions/                  # Elastic Beanstalk configurations
```

---

## ⚙️ **Installation and Setup**

### **1. Clone the repository:**
```bash
git clone (https://github.com/Viplove0114/Students_Performance_ML-project)
cd Students_Performance_ML-project-main
```

### **2. Create a virtual environment (optional but recommended):**
```bash
python -m venv venv
source venv/bin/activate  # For Linux
venv\Scripts\activate     # For Windows
```

### **3. Install dependencies:**
```bash
pip install -r requirements.txt
```

---

## 🛠️ **Usage**

### **1. Run the Application:**
```bash
python app.py
```

### **2. Access the Web Interface:**
- Open your browser and go to: `http://127.0.0.1:5000`
- Enter student details and predict performance.

---

## 📊 **Model Training and Evaluation**
- **Model:** CatBoost (Gradient Boosting Library)
- **Metrics:**
  - R2 Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)

---

## 📚 **Configuration**
The project uses a `Setup.py` file to handle configurations.

---

## 🖥️ **Visualization and Results**
- Perform **EDA** using the Jupyter notebooks in the `Notebook/` folder.
- View training logs in the `logs/` folder.

---

## 🛠️ **Troubleshooting**
- Ensure all dependencies are installed.
- Check the `logs/` folder for errors.
- Restart the application after any code changes.

---

## 📬 **Contact**
For any inquiries or issues, feel free to reach out: **Viplove Thakran**
[viplovethakran4@gmail.com

---

## ⚖️ **License**
This project is licensed under the MIT License.

