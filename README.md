# Functionality
🛡️ Admin
URL: /admin_dashboard/

Functionalities:
Add/Delete Doctors
Add/Delete Patients
Approve or Reject Appointment Requests
View all records and system statistics
Generate Invoices for discharged patients

🧑‍⚕️ Doctor
URL: /doctor_dashboard/

Functionalities:
View today's appointments
View patient history
View and manage assigned patients
Delete appointments after treatment
Track discharged patient records

🧑 Patient
URL: /patient_dashboard/

Functionalities:
Register/Login
Book new appointments
View assigned doctor details and department
Download discharge invoice
View appointment status

# Structure
hospital_management/
│
├── hospital_app/
│   ├── migrations/
│   ├── templates/
│   │   ├── all html files.......
│   ├── static/
│   │   ├── css/
│   │   ├── js/
        ├── images/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   └── admin.py
│
├── hospital_management/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── db.sqlite3
├── manage.py
└── README.md

💻 Installation
**Step 1:Clone the Repository**
git clone https://github.com/your-username/hospital-management-system.git
cd hospital-management-system

**Step 2:Create a Virtual Environment and Activate It**
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

**Step 3:Install Dependencies**
pip install -r requirements.txt

**Step 4:Run Migrations**
python manage.py makemigrations
python manage.py migrate

**Step 5:Create Superuser (Admin)**
python manage.py createsuperuser

**Step 6:Run the server**
python manage.py runserver



# Screenshots
See in images folder within static files

