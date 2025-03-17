# Simple Flask Web Application

A minimal Flask web application that demonstrates basic form handling and user input echo functionality.

## Setup Instructions

1. Create and activate a virtual environment:

```bash
python -m venv venv
# On Windows:
.\venv\Scripts\activate
# On Unix or MacOS:
source venv/bin/activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the application:

```bash
# Set the Flask application
# On Windows:
$env:FLASK_APP="src/app.py"
# On Unix or MacOS:
export FLASK_APP=src/app.py

# Run the application
flask run
```

4. Run tests:

```bash
pytest
```

## Features

- Simple web form that accepts user input
- Displays the user's input back on the screen
- Basic test coverage
- Ready for Heroku deployment

## Deployment

This application is configured for deployment on Heroku. The `Procfile` and `requirements.txt` are already set up for this purpose.
