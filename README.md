# ExpenseEaze

## Setup Instruction

To set up ExpenseEaze locally, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/Vikuuu/Expense-Tracker.git
```

2. Navigate to the project directory:

```bash
cd ExpenseEaze
```

3. Install the required dependencies:

```bash
pipenv install
```

4. Run migrations to create the database schema:

```bash
python manage.py migrate
```

5. Start the development server:

```bash
python manage.py runserver
```

6. Access the application at [http://localhost:8000](http://localhost:8000).
