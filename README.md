# Smart Health Tracker

A Django web application that connects **patients, doctors and therapists** on one platform for health tracking, appointments, therapy tasks and emergency alerts.

> **Disclaimer:** This is an academic project and is not a certified medical product.

## Features

**Patients**
- Register and log in with a dedicated patient account and unique ID
- Submit daily health logs and mood logs
- Book and manage appointments with hospitals and doctors
- Complete therapy tasks assigned by their therapist
- Send an **SOS emergency alert** to doctors and therapists
- Watch exercise videos and chat with their care team

**Doctors**
- Dashboard with patient lookup by unique ID
- Log and update visit records, upload prescriptions and reports
- View patient progress charts and improvement scores
- SOS alert center to acknowledge and resolve emergencies
- Confirm or cancel appointments

**Therapists**
- Assign tasks, add notes and feedback on patient progress
- Upload and manage an exercise video library
- Receive emergency alerts

## Tech Stack

Python, Django 5.2, SQLite, HTML/CSS, JavaScript

## Getting Started

**Prerequisites:** Python 3.10+

```bash
git clone https://github.com/vilasvilas1052005-png/Smart-Health-Tracker.git
cd Smart-Health-Tracker
python -m venv venv
venv\Scripts\activate          # Windows
# source venv/bin/activate     # macOS / Linux
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Open http://127.0.0.1:8000 and register as a patient, doctor or therapist.

## Project Structure

```
smart_health/    Django project settings and URLs
core/            Main app: models, views, forms, templates
manage.py        Django management script
```

## Notes

- The database and uploaded files (photos, prescriptions, reports) are not included, so you start with a clean setup.
- `SECRET_KEY` and `DEBUG=True` in `settings.py` are for development only. Use environment variables for production.

## Author

**Vilas N** — Information Science Engineering student, Malnad College of Engineering, Hassan.
GitHub: [vilasvilas1052005-png](https://github.com/vilasvilas1052005-png)
