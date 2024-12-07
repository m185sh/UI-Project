Django-Based TestZeus UI Project
A lightweight and user-friendly web application built with Django to serve as a UI facade over the testzeus-hercules system. The project allows users to interact with the testzeus-hercules API through an intuitive interface.

Features
Simple and Clean UI: Easy-to-use interface for submitting queries and viewing results.
Django Framework: Reliable backend with robust error handling and API integration.
Responsive Design: Optimized for different screen sizes.
Lightweight Implementation: Minimal setup and maintenance requirements.
Project Structure
testzeus_ui/
├── testzeus_ui/         # Django project settings
│   ├── settings.py      # Configuration
│   ├── urls.py          # Project-level URL routing
│   ├── wsgi.py          # WSGI configuration
├── app/                 # Main app folder
│   ├── templates/       # HTML templates
│   │   ├── app/         
│   │       ├── index.html
│   │       ├── result.html
│   ├── static/          # Static assets
│   │   ├── app/         
│   │       ├── style.css
│   ├── views.py         # View functions
│   ├── urls.py          # App-level URL routing
│   ├── models.py        # Database models (not used in this project)
├── manage.py            # Django's command-line utility
├── requirements.txt     # Python dependencies
Prerequisites
Python 3.8 or later
pip (Python package manager)
Django (Installed via pip
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/django-testzeus-ui.git
cd django-testzeus-ui
Create a Virtual Environment (Optional but recommended):

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Run Migrations:

bash
Copy code
python manage.py migrate
Start the Development Server:

bash
Copy code
python manage.py runserver
Access the App: Open your browser and navigate to http://127.0.0.1:8000.

Usage
Open the application in your browser.
Enter a query in the input field and submit it.
View the response from the testzeus-hercules API on the result page.
Configuration
Replace the API_BASE_URL in app/views.py with the actual URL of the testzeus-hercules API:
python
Copy code
API_BASE_URL = "http://example.com/api"
Screenshots
Homepage:

Result Page:

Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

License
This project is licensed under the MIT License.

Contact
For questions or feedback, please reach out to:

Name: [mahesh babu halavath]
Email: [maheshhalavath17@gmail.com]
GitHub: [https://github.com/m185sh]
