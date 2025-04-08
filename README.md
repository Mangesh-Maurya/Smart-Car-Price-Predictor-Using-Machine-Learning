🚗 Car Price Predictor
A simple Flask web application that predicts the selling price of a used car based on its features like brand, model, year, fuel type, and kilometers driven.

🔍 Features
Predicts accurate car prices using a trained machine learning model.

Dynamic dropdown for car model based on selected company.

Clean UI with Bootstrap styling.

AJAX-based form submission – prediction shown without page reload.

🛠️ Tech Stack
Backend: Python, Flask

Frontend: HTML, CSS, Bootstrap, JavaScript (Vanilla JS)

Modeling: scikit-learn, pandas, NumPy

📦 Installation
bash
Copy
Edit
git clone https://github.com/your-username/car-price-predictor.git
cd car-price-predictor
pip install -r requirements.txt
python app.py
Access the app at: http://127.0.0.1:5000/

📁 Project Structure
cpp
Copy
Edit
car-price-predictor/
│
├── static/
│   └── css/
│       └── style.css
├── templates/
│   └── index.html
├── model/
│   └── car_price_model.pkl
├── app.py
├── requirements.txt
└── README.md
💡 How It Works
Load car dataset, train a regression model.

User selects car details via the form.

App sends the data via AJAX to Flask backend.

Backend returns the predicted price without page reload.

📸 Screenshot

📜 License
MIT License![Screenshot (18)](https://github.com/user-attachments/assets/337a09c4-8cdf-4eed-9ee0-f0cc9169562e)
![Screenshot (17)](https://github.com/user-attachments/assets/ffc07d6b-b42e-4054-bbbf-590db7c10b41)
