HDI Prediction System — A Comprehensive Measure of Well-Being
📌 Project Summary
HDI Prediction System is an AI-powered Human Development Index prediction platform developed to simplify the assessment of human development levels across countries using machine learning. Instead of manually analyzing complex datasets with 195 countries and 82 indicators, the system takes four key socioeconomic inputs — Life Expectancy, Mean Years of Schooling, Gross National Income per capita, and Internet Users — and instantly predicts the HDI score along with its development category.
Rather than replacing analysts or researchers, the HDI Prediction System acts as an intelligent decision-support tool that enables faster, more consistent, and more accessible human development insights for policymakers, researchers, students, and development organizations worldwide.

✨ Key Features

Instant HDI score prediction using a trained Linear Regression model
HDI category classification — Low, Medium, High, and Very High HDI
Data preprocessing pipeline with automated null value handling
Professional Flask web application with Home, Prediction Form, and Result pages
Three interactive analytics dashboards — HDI Score Comparison, World HDI Map, and HDI Trend Over Years
Model serialization using Pickle for instant loading without retraining
Clean professional dark Navy UI theme across all pages


🏗️ Technical Architecture
The project follows a modular three-layer architecture:
Machine Learning Layer: Handles data loading, exploratory data analysis, preprocessing, feature selection, and model training using Linear Regression. Evaluates performance using R-squared score and serializes the model using Pickle.
Backend Layer: Implemented using Flask, managing HTTP routes, user input processing, model loading, HDI prediction logic, category classification, and result rendering across all pages including the analytics dashboard.
Presentation Layer: Built with HTML5, CSS3, JavaScript, and Chart.js for a professional and responsive user experience including three interactive dashboards with bar charts, pie charts, doughnut charts, line charts, and radar charts.

👥 Team Members
S.NoNameRoleEmail1Spandhana MondamTeam Leadr210961@rguktrkv.ac.in2Bhagyalatha KadaliMemberlathakadali93@gmail.com3Pechetti Lilly Lakshmi Puja SriMembers210417@rguktsklm.ac.in4Balla Kamala AnjaliMemberballakamalaanjali@gmail.com5Gara BhandhaviMemberbhandhavigara@gmail.com

🚀 How to Run the Application
Prerequisites

Python 3.x installed and available in PATH
pip package manager available
Anaconda or VS Code recommended

Step 1: Navigate to the Flask Folder
The complete source code of the application is located inside the Flask directory.
cd Flask
Step 2: Install Project Dependencies
Install all required Python libraries.
pip install numpy pandas matplotlib scikit-learn flask seaborn
Step 3: Generate the Machine Learning Model File
Before launching the web application, open the Jupyter Notebook and run all cells to generate the trained model file.
Training/HumDevIndex.ipynb → Run All Cells
This process loads the HDI dataset, preprocesses the data, trains the Linear Regression model, evaluates performance, and saves the model as HDI.pkl inside the Flask folder.
Step 4: Launch the Flask Web Application
Start the server using:
python app.py
Step 5: Open the Application
Visit the following URL in your web browser:
http://127.0.0.1:5000

🧪 Testing the Prediction
Enter these sample values to verify the prediction is working correctly:
IndicatorSample ValueLife Expectancy72.5Mean Years of Schooling10.2GNI per capita15000Internet Users (%)65.4
Expected Result: High HDI — 0.76 ✅

📂 Project Structure
hdi-prediction-ml/
├── 1. Brainstorming & Ideation/
├── 2. Requirement Analysis/
├── 3. Project Design Phase/
├── 4. Project Planning Phase/
├── 5. Project Development Phase/
├── 6. Project Testing/
├── 7. Project Documentation/
├── 8. Project Demonstration/
│
├── Dataset/
│   └── HDI.csv
│
├── Training/
│   └── HumDevIndex.ipynb
│
├── Flask/
│   ├── app.py
│   ├── HDI.pkl
│   └── templates/
│       ├── home.html
│       ├── indexnew.html
│       ├── resultnew.html
│       └── dashboard.html
│
└── README.md

1. Brainstorming & Ideation/ to 8. Project Demonstration/ — Documentation and project lifecycle phases
Dataset/ — Contains HDI.csv with 195 countries and 82 human development features
Training/ — Jupyter Notebook with complete ML pipeline from data loading to model saving
Flask/app.py — Flask web application handling all routes and prediction logic
Flask/HDI.pkl — Serialized trained Linear Regression model loaded at app startup
Flask/templates/ — HTML pages for Home, Prediction Form, Result, and Dashboard


🙏 Acknowledgement
We sincerely thank SmartBridge for providing this incredible internship opportunity under the domain of Artificial Intelligence and Machine Learning. This project helped us experience the complete AI/ML lifecycle — from raw data exploration and model training all the way to a fully deployed working web application with interactive analytics dashboards.
Project ML-0027 | SmartBridge Internship | SkillWallet Platform
