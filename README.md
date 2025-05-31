# Clinic Management System (HIS)

A comprehensive Hospital Information System (HIS) for managing patient booking, diagnostics, medical records, prescriptions, and appointments.

## Features
- Patient registration and booking system
- Medical diagnosis tracking
- Electronic medical records and prescriptions
- Appointment scheduling and management
- User roles and permissions (doctors, staff, admins)

## Technologies Used
- Python 3
- Django Framework
- MongoDB for medical records
- MySQL for transactional data
- REST APIs

## Installation
1. Clone the repository  
   `git clone https://github.com/yourusername/clinic-management-system.git`
2. Create and activate a virtual environment  
   `python -m venv env`  
   `source env/bin/activate` (Linux/macOS) or `env\Scripts\activate` (Windows)
3. Install dependencies  
   `pip install -r requirements.txt`
4. Configure database settings in `settings.py`
5. Run migrations  
   `python manage.py migrate`
6. Start the server  
   `python manage.py runserver`

## Usage
Access the system via `http://localhost:8000`. Login credentials will be provided by the administrator.

## Contribution
Contributions are welcome. Please create a pull request with a clear description of changes.

## License
