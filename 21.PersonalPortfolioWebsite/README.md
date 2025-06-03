# Personal Portfolio Website (Flask)

An intermediate-level personal portfolio website built with Python and Flask.  
Showcase your skills, projects, and blog posts, and provide a way for visitors to contact you.

---

## Features

### Core Features
- **About Me**: Personal introduction with profile image and bio.
- **Project Showcase**: Dynamically display your projects loaded from JSON or database.
- **Contact Form**: Visitors can send messages via a contact form; emails are sent using SMTP.
- **Skills Section**: Display your technical skills with progress bars or tags.
- **Responsive Design**: Mobile-friendly layout using Bootstrap.
- **Blog (Optional)**: Manage and display blog posts with support for Markdown or database storage.
- **Theme Support**: Light and dark mode toggle with persistent user preference.

### Advanced Features (Optional / Planned)
- **Mini CMS for Blog**: Add, edit, and categorize blog posts with pagination.
- **AI Resume Assistant**: Interactive Q&A about your experience using AI.
- **Search Functionality**: Search through projects and blog posts dynamically.
- **Visitor Analytics**: Track site visits with logging or Google Analytics integration.
- **Admin Login & Management**: Secure admin panel to manage projects, blog posts, and content.
- **SEO Optimization**: Meta tags for better search engine ranking and social sharing.
- **Portfolio Image Carousel**: Showcase project screenshots in an interactive carousel.
- **Resume Download**: Provide downloadable resume PDF.
- **Unit Testing**: Automated tests for routes, forms, and data loading.

---

## Getting Started

### Prerequisites

- Python 3.6+
- Flask
- `python-dotenv` (for environment variables)
- SMTP email account (e.g., Gmail) for contact form

### Installation

## Create a virtual environment and activate it:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

## Install dependencies

pip install -r requirements.txt

## Create a .env file in the project root with your email credentials:
EMAIL_USER=youremail@example.com
EMAIL_PASS=yourpassword
EMAIL_TO=yourdestination@example.com
SECRET_KEY=your_secret_key_here

## Run the application:
python app.py


Open your browser and go to http://127.0.0.1:5000/

## Project Structure

PersonalPortfolioWebsite/
├── app.py                 # Flask application
├── data/
│   └── projects.json      # Project data (can be replaced with DB)
├── templates/             # HTML templates
│   ├── base.html
│   ├── index.html
│   ├── projects.html
│   └── contact.html
├── static/                # CSS, images, JS
├── .env                   # Environment variables (email config)
├── requirements.txt       # Python dependencies
└── README.md

