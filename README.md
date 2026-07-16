🚗 EcoDrive AI

AI-Powered E20 Fuel Compatibility & Predictive Engine Health Diagnostics


---

🌟 Overview

EcoDrive AI is an AI-powered predictive diagnostics platform designed to help vehicle owners safely transition to E20 (20% Ethanol Blended Petrol).

Rather than relying only on a vehicle's manufacturing year, EcoDrive AI analyzes engine health using machine learning and OBD-II-inspired telemetry to predict compatibility, detect early degradation, and recommend preventive maintenance before expensive failures occur.

The project supports India's sustainable mobility mission by enabling data-driven decisions for cleaner transportation.

---

❗ Problem Statement

India is rapidly adopting E20 ethanol-blended fuel to reduce emissions and fuel imports.

However, millions of existing vehicles were not originally designed for higher ethanol concentrations, leading to risks such as:

- Fuel tank corrosion
- Rubber hose degradation
- Injector wear
- Lean combustion
- Engine overheating
- Reduced engine life
- Increased maintenance costs

Most existing solutions simply check manufacturing year and cannot evaluate the actual health of an engine.

---

💡 Solution

EcoDrive AI combines:

- Machine Learning
- Feature Engineering
- Explainable AI
- Rule-Based Diagnostics

to provide personalized engine health predictions and maintenance recommendations.

The system identifies vehicles at risk before major failures occur, helping owners make informed maintenance decisions.

---

## ✨ Features

- 🚗 Synthetic Indian Automotive Data Generator
- 📡 OBD-II Telemetry Simulation
- ⚙️ Feature Engineering
- 🤖 Random Forest Classifier
- 🚨 Vehicle Risk Classification
- 📊 Classification Report
- 📉 Confusion Matrix
- 📈 Feature Importance Analysis
- ⛽ Dynamic E20 Compatibility Advisor
- 💡 Rule-Based Recommendation Engine

---

🧠 How It Works

Vehicle Data
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Machine Learning Model
(Random Forest)
      │
      ▼
Engine Health Prediction
      │
      ▼
Maintenance Recommendation

---

📊 Dataset

The project utilizes a realistic synthetic automotive dataset representing Indian vehicles.

| Field | Description |
|--------|-------------|
| Vehicle Type | Type of vehicle (Hatchback, Sedan, SUV, etc.) |
| Brand | Vehicle manufacturer |
| Manufacturing Year | Year the vehicle was manufactured |
| Engine Capacity | Engine displacement (cc) |
| Odometer | Total distance traveled (km) |
| Fuel System | Type of fuel injection system |
| STFT | Short-Term Fuel Trim (%) |
| Exhaust Gas Temperature (EGT) | Engine exhaust temperature (°C) |
| O₂ Sensor Voltage | Oxygen sensor voltage (V) |
| Misfire Count | Number of engine misfires detected |
| Risk Target | Vehicle risk category (Low, Medium, High) |

---

⚙️ Machine Learning Pipeline

Data Preprocessing

- Missing Value Handling
- Label Encoding
- Feature Engineering
- Train-Test Split

Feature Engineering

- Thermal Stress Index
- BS6 Compatibility Flag
- Fuel System Encoding
- Engine Performance Indicators

Model

Random Forest Classifier

Chosen because it:

- Handles nonlinear relationships
- Is resistant to overfitting
- Works well on mixed feature types
- Provides feature importance for explainability

---

📈 Model Evaluation

The notebook evaluates the model using:
-Accuracy: 94%
-Precision
-Confusion Matrix
-Feature Importance
- Recall
- F1 Score
- Classification Report
- Confusion Matrix
- Feature Importance

---

🛠️ Tech Stack

Category| Technologies
Programming| Python
Data Analysis| Pandas, NumPy
Machine Learning| Scikit-learn
Visualization| Matplotlib, Seaborn
Development| Jupyter Notebook

---

📂 Project Structure

EcoDriveAI/
│
├── BuildINAI.ipynb
├── README.md
└── EcoDriveAI_Hackathon_Pitch_Deck.pdf

---

▶️ Getting Started

Clone Repository

git clone https://github.com/shiksha5245/EcoDriveAI-E20.git
Install Dependencies

pip install -r requirements.txt

Launch Notebook

jupyter notebook BuildINAI.ipynb

---

📌 Future Scope

- Real OBD-II integration
- Live vehicle diagnostics
- Mobile application
- IoT monitoring
- Cloud deployment
- Explainable AI (SHAP/LIME)

---

🌍 Impact

EcoDrive AI contributes to:

- Sustainable Transportation
- Cleaner Fuel Adoption
- Lower Maintenance Costs
- Early Fault Detection
- Data-Driven Vehicle Diagnostics
- Support for India's Green Mobility Initiative

---

🏆 Hackathon Highlights

- AI + Sustainability Solution
- Machine Learning Powered Diagnostics
- Explainable Predictions
- Preventive Maintenance Approach
- Practical Real-World Use Case
- Scalable Architecture

---

👩‍💻 Author

Shiksha Kumari

Data Science | Machine Learning | Artificial Intelligence | Business Analytics

Driven by a passion for solving real-world challenges through AI, predictive analytics, and data-driven innovation.

---

⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.

Your support motivates continuous innovation and improvement.

---

📜 License

This project is released under the MIT License.
