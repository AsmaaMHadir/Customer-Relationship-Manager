# CRM Application

The CRM Application is a comprehensive backend customer relationship management solution built using Django. It allows users to manage customer records, including viewing, adding, updating, and deleting customer information. The application utilizes PostgreSQL to store customer data and integrates with Railway Apps for efficient database management and querying.

- Client card view
<img width="465" alt="clientView" src="https://github.com/AsmaaMHadir/Django-CRM/assets/46932156/7ed1fde3-9b53-4242-abd8-1b99bec8f35d">

- Full records view for authenticated users:
  <img width="925" alt="mainView" src="https://github.com/AsmaaMHadir/Django-CRM/assets/46932156/8c9ed243-1953-47b7-8516-919e7ff8d057">




## Features

- View a list of customer records with their corresponding IDs.
- Add new customer records with detailed information.
- Update existing customer records to reflect the latest information.
- Delete customer records that are no longer needed.

## Technologies Used

- Django
- PostgreSQL
- Railway Apps

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/crm-application.git <----
   cd crm-application
   ```
   
2. **Create a virtual environment and activate it:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

   ```

3. **Install the project dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up the PostgreSQL database:**
Create a PostgreSQL database and update the database settings in settings.py.

5. **Run the migrations and create a superuser:**
   
```bash
python manage.py migrate
python manage.py createsuperuser

```

6. **Run the development server:**

```bash
python manage.py runserver
```

## Usage

- Access the application through the provided URL (e.g., http://localhost:8000).

- Log in using the superuser account created during installation.

- Navigate to the CRM dashboard to manage customer records.

## Database Management with Railway Apps
Railway Apps is used to seamlessly manage the PostgreSQL database. You can view and query database tables easily through the Railway Apps interface.

## Contributing
Contributions are welcome! Feel free to submit issues and pull requests.


## Contact
For any inquiries, please reach out to me over asmaahadir11@gmail.com
