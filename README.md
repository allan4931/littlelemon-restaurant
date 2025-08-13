# Little Lemon Restaurant

A Django-based restaurant web application for Little Lemon, based in Chicaco, USA.

## Features

- Menu listing and detail pages
- Booking system
- About Us page
- Static assets for branding

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/allan4931/littlelemon-restaurant.git
   cd littlelemon-restaurant
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python3 -m venv env
   source env/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations:**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

## Usage

- Visit `http://127.0.0.1:8000/` in your browser.
- Use the navigation links to view the menu, book a table, or learn more about us.

