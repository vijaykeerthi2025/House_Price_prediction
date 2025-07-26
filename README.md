# House_Price_prediction
A machine learning-based project that predicts the price of a house based on key features such as location, area, number of bedrooms, and amenities. This project uses regression techniques to deliver accurate price estimations and includes a simple web interface for user interaction.
# 🏠 House Price Prediction with Flask and Machine Learning

This project is a *web-based house price prediction application* built using *Python, **Machine Learning (scikit-learn), and **Flask*.  
It predicts the price of a house based on features like *area, number of bedrooms, bathrooms, location, condition, and garage availability*.

---

## 🚀 *Features*
- *Machine Learning Model* trained on real-world house price data.
- *Flask Web Interface* for predicting prices interactively.
- *User-friendly web form* to enter house details.
- *Responsive design* with modern UI and background image.
- *Model files saved with Pickle* for fast predictions.

---

## 🗂 *Project Structure*
house_price_project/ │ ├── app.py                # Flask web server ├── model.py              # ML training script (train & save model) ├── house_data.csv        # Dataset used for training ├── model.pkl             # Trained ML model ├── scaler.pkl            # StandardScaler object ├── label_encoder.pkl     # Encoded locations │ ├── templates/            # HTML templates (Flask Jinja2) │    └── index.html │ └── static/               # CSS and images └── style.css
---

## 🧠 *Technologies Used*
- *Python 3*
- *Flask (Web Framework)*
- *Pandas, NumPy*
- *Scikit-Learn (ML Model)*
- *Pickle (Model Serialization)*
- *HTML, CSS (Frontend)*

---

## ⚙ *How to Run the Project*
Follow these steps to run it locally:

### *1. Install Python*
[Download Python](https://www.python.org/downloads/) and make sure to check *"Add to PATH"* while installing.

### *2. Clone or Download*
```bash
git clone https://github.com/your-username/house_price_project.git
cd house_price_project
3. Install Dependencies

pip install -r requirements.txt

(Create a requirements.txt file with packages like flask, pandas, numpy, scikit-learn.)

4. Train the Model

python model.py

5. Start the Flask Server

python app.py

6. Open in Browser

Visit http://127.0.0.1:5000/ in your browser.


---

📊 Dataset

The dataset contains:

Area (sq.ft)

Bedrooms

Bathrooms

Floors

Year Built

Location

Condition (Poor, Average, Good, Excellent)

Garage (Yes/No)

Price (Target Variable)

Results:
I uploaded my result screenshot in screenshot1.png file

✨ Future Improvements

Add real-time house price data from APIs.

Deploy the project on Heroku or Render.

Use Deep Learning (ANN) for better predictions.

👨‍💻 Author

Developed by [Keerthana K G]
Contact: kgkeerthana693@gmail.com
