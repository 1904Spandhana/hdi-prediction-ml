🌐 A Comprehensive Measure of Well-Being

HDI Prediction System | ML-0027 | SmartBridge Internship


📌 Project Summary

HDI Prediction System is an AI and Machine Learning based web application developed to predict the Human Development Index (HDI) score of any country using four key socioeconomic indicators.

The system eliminates the need for complex manual analysis of large datasets by providing an instant, accurate, and user-friendly prediction tool accessible through a web browser. It acts as an intelligent decision-support tool for policymakers, researchers, students, and development analysts to quickly assess and compare human development levels across nations.


✨ Key Features


🔮 Instant HDI score prediction using a trained Linear Regression model
📊 HDI category classification — Low / Medium / High / Very High
🧹 Data preprocessing pipeline with null value handling using column mean imputation
🌐 Professional Flask web application with Home, Prediction Form and Result pages
📈 Three interactive Analytics Dashboards:

HDI Score Comparison (Bar Chart — Top 20 & Bottom 10 countries)
World HDI Map (Country cards with category filter + Pie & Doughnut charts)
HDI Trend Over Years (Line chart 1990–2015 + Radar chart)



💾 Model serialization using Pickle (HDI.pkl) for instant loading without retraining
🎨 Clean professional dark Navy UI theme across all pages



🏗️ Technical Architecture

ML Layer       →  Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, Pickle
Backend Layer  →  Flask (Python), Jinja2 Templates
Frontend Layer →  HTML5, CSS3, JavaScript, Chart.js


📊 Dataset

PropertyDetailsSourceKaggle — Human Development Index DatasetSize195 rows (countries) × 82 columnsTarget VariableHDI Score (column index 4)Input FeaturesLife Expectancy, Mean Years of Schooling, GNI per capita, Internet UsersPreprocessingMissing values filled with column mean


📂 Project Structure

hdi-prediction-ml/
│
├── Dataset/
│   └── HDI.csv                    ← Dataset (195 countries, 82 features)
│
├── Training/
│   └── HumDevIndex.ipynb          ← Jupyter Notebook (full ML pipeline)
│
├── Flask/
│   ├── app.py                     ← Flask backend
│   ├── HDI.pkl                    ← Saved trained model
│   └── templates/
│       ├── home.html              ← Home page
│       ├── indexnew.html          ← Prediction input form
│       ├── resultnew.html         ← Prediction result page
│       └── dashboard.html         ← Analytics dashboard
│
├── 1. Brainstorming & Ideation/
├── 2. Requirement Analysis/
├── 3. Project Design Phase/
├── 4. Project Planning Phase/
├── 5. Project Development Phase/
├── 6. Project Testing/
├── 7. Project Documentation/
├── 8. Project Demonstration/
└── README.md


🚀 How to Run the Application

Prerequisites


Python 3.x installed
pip package manager
Anaconda or VS Code (recommended)


Step 1 — Install Required Libraries

bashpip install numpy pandas matplotlib scikit-learn flask seaborn

Step 2 — Set Up Project Folder

Ensure the folder structure matches the above with Dataset/HDI.csv present.

Step 3 — Train the Model

Open Training/HumDevIndex.ipynb in Jupyter Notebook and run all cells.
This generates Flask/HDI.pkl.

Step 4 — Launch the Flask Application

bashcd Flask
python app.py

Step 5 — Open the Application

Visit in your browser:

http://127.0.0.1:5000


🧪 Test the Prediction

Enter these sample values to test:

IndicatorSample ValueLife Expectancy72.5Mean Years of Schooling10.2GNI per capita15000Internet Users (%)65.4

Expected Result: High HDI — 0.76 ✅


👥 Team Members

S.NoNameRole1Spandhana MondamTeam Lead2Bhagyalatha KadaliMember3Pechetti Lilly Lakshmi Puja SriMember4Balla Kamala AnjaliMember5Gara BhandhaviMember


🛠️ Technology Stack

LayerTechnologiesMachine LearningPython, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, PickleBackendFlask, Jinja2FrontendHTML5, CSS3, JavaScript, Chart.jsData SourceKaggle — HDI DatasetVersion ControlGit & GitHub


🙏 Acknowledgement

We sincerely thank SmartBridge for providing this incredible internship opportunity under the domain of Artificial Intelligence & Machine Learning. This project helped us experience the complete AI/ML lifecycle — from raw data all the way to a fully deployed working application.


Project ML-0027 | SmartBridge Internship | SkillWallet Platform
