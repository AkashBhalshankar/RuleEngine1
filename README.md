# Rule Engine with Django

## Project Description
This project implements a rule engine that allows users to define and evaluate dynamic rules based on various attributes like age, department, salary, etc. The rules are represented using an Abstract Syntax Tree (AST), enabling flexible rule creation, modification, and evaluation. The project is built using Django for the backend and HTML/CSS for the frontend.

## Features
- Create rules dynamically through a web interface.
- Store and evaluate rules using ASTs for efficient processing.
- Combine multiple rules with logical operators (AND/OR).
- Real-time rule evaluation based on user input.
- Built using Django, HTML, and CSS.

## Technologies Used
- Django (backend)
- HTML & CSS (frontend)
- SQLite (database)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/rule-engine-django.git
    ```

2. Navigate to the project directory:
    ```bash
    cd rule-engine-django
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```bash
    python manage.py migrate
    ```

5. Run the development server:
    ```bash
    python manage.py runserver
    ```

6. Access the application in your browser:
    ```
    http://127.0.0.1:8000/
    ```

## Usage
- **Create a Rule**: Go to the "Create Rule" page, enter a rule (e.g., `age > 30 AND department = 'Sales'`), and submit.
- **Evaluate a Rule**: Input the attributes (age, department, etc.) for evaluation against the rules you've created.

## Example Rules
- `(age > 30 AND department = 'Sales') OR (age < 25 AND department = 'Marketing')`
- `(age > 30 AND salary > 50000)`

## Testing
To run tests:
```bash
python manage.py test



