# 🌍 Multiple Disease Prediction System Using Machine Learning

## ✨ Overview
The **Multiple Disease Prediction System** is a machine learning-based web application that predicts multiple diseases, 
including ** Heart Disease, Liver Disease, and Diabetes**, based on user-provided symptoms and test results.
It leverages machine learning algorithms such as **🌟 Random Forest, ⚙️ XGBoost, and 🔎 K-Nearest Neighbors (KNN)** to provide accurate predictions.

## 💡 Features
- ✅ Predicts **Heart Disease, Liver Disease, and Diabetes**.
- 🌀 Uses **machine learning models** trained on real-world datasets.
- 🛠️ Web-based interface using **Django Framework**.
- 🔧 Interactive **user and admin modules**.
- 🛡️ Integrated **API for communication** between the frontend and backend.

## ⚛️ Technologies Used
### 💻 Programming Language:
- **🔍 Python** (for model training and backend)

### 👩‍🎓 Machine Learning Libraries:
- **🌟 scikit-learn** (RandomForest, KNN)
- **⚙️ XGBoost**
- **🧠 pandas, NumPy** (Data Processing)
- **📊 matplotlib** (Data Visualization)

### 🌐 Web Frameworks & Tools:
- **🏢 Django** (Backend)
- **📝 HTML, CSS, JavaScript** (Frontend UI)
- **🌈 Bootstrap** (Responsive Web Design)

## 📂 Project Structure
```
Multiple-Disease-Prediction/
│-- dataset/               # 📊 Contains training datasets
│-- models/                # 🛠️ Trained machine learning models (Pickle files)
│-- static/                # 👾 CSS, JS, Images
│-- templates/             # 🌐 HTML templates for frontend
│-- disease_prediction/    # 🎮 Django App for prediction
│   │-- views.py           # 🛏 Handles API and user requests
│   │-- urls.py            # 🌍 URL routing
│   │-- models.py          # 📃 Database models (if needed)
│-- manage.py              # 🎓 Django Management Script
│-- requirements.txt       # 🎩 Dependencies list
│-- README.md              # 📖 Project Documentation
```

## 🚀 Installation & Setup
1. **📚 Clone the Repository**
   ```sh
   git clone https://github.com/your-repo/multiple-disease-prediction.git
   cd multiple-disease-prediction
   ```
2. **🧙 Create a Virtual Environment & Install Dependencies**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```
3. **🏢 Run Migrations** (if using database)
   ```sh
   python manage.py migrate
   ```
4. **🚪 Run the Application**
   ```sh
   python manage.py runserver
   ```
5. **📱 Access the Web App**
   Open `http://127.0.0.1:8000/` in your browser.

## 🌐 Usage
1. **👤 User Registration/Login**
2. **⚕️ Enter Symptoms and Medical Test Values**
3. **🔢 Predict Disease**
4. **🎉 View Results and Suggestions**

## 📊 Machine Learning Models & Accuracy
| ⚕️ Disease  | ⚙️ Algorithm  | 📊 Accuracy |
|----------|-----------|----------|
| 💜 Diabetes | Random Forest  | 85%  |
| ❤️ Heart Disease | Random Forest | 70%  |
| 🌟 Liver Disease | XGBoost | 80% |

## ✨ Future Enhancements
- 🎮 Integration of **more diseases**.
- 📱 **Mobile-friendly UI**.
- 🧠 Improved **explainability** of model predictions.

