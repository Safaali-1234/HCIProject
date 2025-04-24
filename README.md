🛍️ Django Product Selling Website
This is a simple e-commerce website made using Django (Python) for the backend and HTML, CSS, Bootstrap for the frontend. It allows users to browse products, view details, add items to the cart, and place orders.

✅ What You Can Do
Browse a list of products

View product details

Add/remove items in the shopping cart

Register and log in as a user

Place orders

Admin panel to manage products

🧱 Technologies Used
Backend: Django (Python)

Frontend: HTML, CSS, Bootstrap

Database: SQLite (you can switch to PostgreSQL or MySQL)

Payments: (Optional) Stripe or PayPal integration

Authentication: Django built-in auth system

📂 Folder Structure
bash
Copy
Edit
/project_name/         # Main Django project settings
/store/                # Main app with models and views
/templates/            # HTML templates
/static/               # CSS, JS, and images
/manage.py             # Django management file
⚙️ How to Run the Project
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/django-product-site.git
cd django-product-site
2. Set Up a Virtual Environment
bash
Copy
Edit
python -m venv env
source env/bin/activate    # On Windows use: env\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Run Migrations
bash
Copy
Edit
python manage.py migrate
5. Create Admin User
bash
Copy
Edit
python manage.py createsuperuser
6. Run the Server
bash
Copy
Edit
python manage.py runserver
Now open your browser and go to http://127.0.0.1:8000/

✨ Admin Panel
You can manage products, users, and orders from the Django admin panel:

Visit http://127.0.0.1:8000/admin/ and log in with the superuser credentials.

📌 Notes
All templates use Bootstrap for responsive design.

You can extend this project by adding:

Product categories

Payment gateway integration

Order history

Reviews and ratings
