# MicroBlog

A minimalist blogging platform built with Flask and MongoDB that allows users to create and view blog entries with dates. The application features a clean, responsive design and simple user interface.

## Features

- Create new blog entries
- View all entries with dates
- Responsive design
- Clean and modern UI
- Automatic date formatting
- Entry preview with truncation

## Technologies Used

- **Backend:**
  - Flask
  - MongoDB
  - Python
  - PyMongo

- **Frontend:**
  - HTML5
  - CSS3
  - Jinja2 Templates

## Prerequisites

Before running this project, make sure you have the following installed:
- Python 3.x
- MongoDB
- pip (Python package manager)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/egmndrk/Blog-pythonweb.git
cd microblog
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the root directory and add your MongoDB URI:
```
MONGODB_URI=your_mongodb_connection_string
```

## Running the Application

1. Make sure MongoDB is running on your system

2. Start the Flask application:
```bash
flask run
```

3. Open your web browser and navigate to `http://localhost:5000`

## Project Structure

```
microblog/
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── microblog-logo.svg
│
├── templates/
│   └── home.html
│
├── app.py
├── requirements.txt
└── .env
```

## Author

Egemen Doruk

## Acknowledgments

- Flask documentation
- MongoDB documentation
- Python community
