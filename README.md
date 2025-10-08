Rishabh's Gym Customer Management System 🏋️‍♂️

A web-based system I built to efficiently manage gym customers, memberships, payments, and entry logs. It provides a clean dashboard for admins and a personalized dashboard for customers.

Features:
- Admin Dashboard: View total customers, active memberships, and revenue at a glance.
- Customer Management: Add, update, search, and delete customer profiles.
- Payment Tracking: Record and view customer payments, mark as Paid or Pending.
- Entry Logs: Track customer check-ins and check-outs.
- Customer Dashboard: Customers can view their membership details and payment history.
- Authentication: Secure login for admins and customers with hashed passwords.

Technologies Used:
- Backend: Python, Flask
- Database: SQLite, SQLAlchemy ORM
- Frontend: HTML, Tailwind CSS, Jinja2 templates
- Security: Password hashing with Werkzeug

Installation:
1. Clone the repository:
   git clone <repository-url>
   cd gym-customer-management

2. Create a virtual environment and activate it:
   python -m venv venv
   source venv/bin/activate      # Linux/Mac
   venv\Scripts\activate         # Windows

3. Install dependencies:
   pip install -r requirements.txt

4. Run the application:
   python app.py

5. Open your browser and go to http://127.0.0.1:5000

Default Admin Credentials:
- Email: admin@gym.com
- Password: admin123

You can change these in app.py before running the app.

Usage:
- Admins: Access the admin dashboard, manage customers, payments, and entry logs.
- Customers: Register an account, login, and view personal dashboard and payment history.


License:
This project is open-source. Feel free to use, modify, and improve it.
