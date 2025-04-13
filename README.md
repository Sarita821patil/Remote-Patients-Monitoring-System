# Remote Patient Monitoring System (RPMS)

A Machine Learning and IoT-based healthcare application that enables real-time monitoring and analysis of patient vitals. Designed to track over 5,000 patients, this system predicts potential health risks with 90% accuracy using Logistic Regression and SVM algorithms.

## 💡 Features

- 🩺 Monitors vitals like heart rate, temperature, and oxygen level
- 📡 Real-time data collection via IoT sensors
- 📊 Predictive analytics using ML algorithms (Logistic Regression, SVM)
- 🌐 Web-based dashboard built with Flask
- 💾 Secure data storage with MySQL

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS (basic interface)
- **Backend:** Python, Flask
- **Machine Learning:** Scikit-learn, Pandas, NumPy
- **Database:** MySQL
- **Hardware:** IoT sensors (e.g., DHT11, Pulse Sensor)

## 📈 ML Model Performance

| Algorithm           | Accuracy |
|---------------------|----------|
| Logistic Regression | 90%      |
| SVM                 | 88%      |

## 🏗️ Architecture

1. **Data Collection:** IoT sensors gather patient vitals.
2. **Data Transmission:** Data is sent to the backend server via HTTP.
3. **Prediction:** ML models process data to detect abnormalities.
4. **Storage:** Data is stored and retrieved from a MySQL database.
5. **Dashboard:** Web interface displays patient status and alerts.

## 🔧 Installation

```bash
git clone https://github.com/Sarita821patil/rpms.git
cd rpms
pip install -r requirements.txt
python app.py
