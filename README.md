# LUXORA - Pakistani Fashion E-Commerce Platform

A full-stack e-commerce web application for Pakistani fashion, built with Django. Developed as an internship project, going beyond the core requirements to include an AI-powered shopping assistant, admin order management, and a fully custom, responsive frontend.

## Features

### Customer-facing
- User registration, login, and logout with a custom user model
- Product browsing with category filtering
- Product detail pages with reviews and star ratings
- Shopping cart with quantity controls
- Full checkout flow with shipping address and order confirmation
- Order history for logged-in users
- **AI Shopping Assistant** - a chat interface (powered by Google Gemini) that recommends real products from the catalog based on natural language requests (e.g. "something for a wedding under Rs. 4000")

### Admin-facing
- Full Django admin panel for managing products, categories, and inventory
- Order management with search, status filters, and one-click bulk actions (mark processing/shipped/delivered/cancelled)
- Order status updates reflect live on the customer's order history page

### Design
- Custom Pakistani-fashion-inspired visual identity (maroon, gold, ivory palette)
- Fully responsive layout (mobile, tablet, desktop)
- Animated homepage hero section

## Tech Stack
- **Backend:** Django 6.1, Python 3.13
- **Database:** SQLite (development)
- **AI:** Google Gemini API (gemini-3.1-flash-lite)
- **Frontend:** Django Templates, vanilla CSS/JavaScript
- **Other:** Django REST Framework, Pillow

## Setup Instructions

1. Clone the repository:

git clone <your-repo-url>
cd luxora


2. Create and activate a virtual environment:

python -m venv venv
venv\Scripts\activate


3. Install dependencies:

pip install -r requirements.txt


4. Create a `.env` file in the project root with:

GEMINI_API_KEY=your-gemini-api-key-here


5. Run migrations:

python manage.py migrate


6. Create a superuser:

python manage.py createsuperuser


7. Run the development server:

python manage.py runserver


8. Visit `http://127.0.0.1:8000` to view the site, and `/admin` for the admin panel.

## Screenshots

(screenshots to be added)

## Author

Built by Musfira as part of an internship project.

