Patient Treatment Type Prediction

This project is a Django-based web application that predicts whether a patient should be admitted for in-care treatment or can be treated as an out-patient. The prediction is based on given condition points and patient data.


🚀 Features

Web interface for entering patient condition details.

Predicts patient treatment type (In-care / Out-care).

Simple, professional UI using Django templates.

Stores data in SQLite database.



🛠 Tech Stack

Backend: Python, Django

Frontend: HTML, CSS (Django templates)

Database: SQLite

Data Handling: Pandas, CSV



📂 Project Structure
Patient_treatment_type_Prediction/
 └── Patient-Treatment-Type-Prediction/
      ├── GUI/
      │   ├── manage.py             # Django management script
      │   ├── db.sqlite3            # Default database
      │   ├── basics/               # Main app
      │   │   ├── models.py         # Database models
      │   │   ├── views.py          # Logic for prediction
      │   │   ├── templates/        # HTML files (UI)
      │   │   │   ├── index.html
      │   │   │   ├── about.html
      │   │   ├── data.csv          # Patient data
      │   └── GUI/                  # Django project settings
      │       ├── settings.py
      │       ├── urls.py
      │       ├── wsgi.py
      │       ├── asgi.py




⚙️ Installation & Setup

Clone the repository

git clone https://github.com/your-username/Patient_treatment_type_Prediction.git
cd Patient_treatment_type_Prediction/Patient_treatment_type_Prediction/Patient-Treatment-Type-Prediction/GUI



Create virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows




Install dependencies

pip install -r requirements.txt




If requirements.txt is missing, install manually:

pip install django pandas




Run migrations

python manage.py migrate




Start the development server

python manage.py runserver




Open in browser

http://127.0.0.1:8000/



🎯 Usage

Go to the home page.

Enter patient condition details.

The system predicts whether the patient requires In-care or Out-care treatment.



📌 Future Improvements

Enhance UI with modern styling (Bootstrap / Tailwind).

Add more medical condition features for better accuracy.

Implement authentication for doctors/admins.

Deploy on cloud (Heroku, PythonAnywhere, or AWS).



📝 License

This project is licensed under the MIT License – feel free to use and modify it.