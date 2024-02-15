# Hello World Django App

This is a simple Django app that responds with a Hello World message in JSON format.

## How to Run/Start the Web App

```bash
# Clone the repository
git clone https://github.com/your-username/HelloWorldApp.git

# Navigate to the project directory
cd HelloWorldApp

# Install dependencies
pip install -r requirements.txt

# Apply database migrations
python manage.py migrate

# Start the development server
python manage.py runserver

#Navigate in browser
http://127.0.0.1:8000/hello/
```

Make sure you have Python and Django installed on your machine.

The app has a single endpoint at `/hello/` that responds with a JSON object: `{"Message": "Hello World!"}`.

`HelloWorldApp/`: Django project root directory.
- `hello_world/`: Django app directory containing the Hello World view.
  - `views.py`: Defines the view that returns the Hello World JSON response.
  -`urls.py`: Configures the URL patterns for the app.
- `HelloWorldApp/`: Project-specific settings and configurations.
  - `urls.py`: Main URL configuration for the project.
 
