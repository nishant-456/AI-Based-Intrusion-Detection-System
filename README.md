# AI-Based Intrusion Detection System

An AI-based Intrusion Detection System (IDS) developed using **Python**, **Flask**, and **Machine Learning** to identify and classify network traffic as normal or malicious. The application provides a simple web interface for uploading network traffic data and visualizing prediction results.

---

## Features

- Upload network traffic data in CSV format
- Detect and classify network attacks using a trained machine learning model
- Data preprocessing using a saved scaler and label encoder
- Interactive web interface built with Flask
- Visualization of attack distribution
- Confusion matrix generation (when ground-truth labels are available)
- Timeline visualization of predicted attacks

---

## Technologies Used

- Python
- Flask
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Joblib

---

## Project Structure

```
AI-Based-Intrusion-Detection-System/
│
├── app.py
├── model.py
├── saved_model.h5
├── scaler.pkl
├── label_encoder.pkl
├── requirements.txt
├── README.md
├── .gitignore
│
├── templates/
│   ├── index.html
│   ├── dashboard.html
│   └── results.html
│
├── static/
│   └── plots/
│
└── uploads/
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/ai-based-intrusion-detection-system.git
```

### 2. Navigate to the project directory

```bash
cd ai-based-intrusion-detection-system
```

### 3. Install the required dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

## How It Works

1. Upload a network traffic CSV file.
2. The application preprocesses the uploaded data.
3. The trained machine learning model predicts the traffic category.
4. Results are displayed through tables and visualizations, including attack distribution and timeline charts.

---

## Future Improvements

- Real-time network traffic monitoring
- Live intrusion alerts
- Improved model performance
- Cloud deployment
- Enhanced dashboard analytics

---

## Author

**Nishant Kirar**

Final Year B.Tech (Artificial Intelligence & Robotics)

Madhav Institute of Technology and Science (MITS), Gwalior

---

## License

This project is intended for educational and learning purposes.
