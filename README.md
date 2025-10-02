# Daily Finances

A FastAPI-based web application for managing personal daily finances. This project allows users to track expenses, incomes, and generate financial reports through a RESTful API.

## Features

- Track daily expenses and incomes
- Categorize transactions
- Generate financial summaries and reports
- RESTful API endpoints

## Technologies Used

- **FastAPI**: Modern, fast web framework for building APIs
- **Python**: Programming language
- **Uvicorn**: ASGI server for running the application

## Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd daily_finances
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the application:
   ```
   uvicorn main:app --reload
   ```

5. Open your browser and navigate to `http://127.0.0.1:8000/docs` to view the interactive API documentation.

## API Endpoints

- `GET /`: Welcome message
- `POST /expenses/`: Add a new expense
- `GET /expenses/`: List all expenses
- `GET /summary/`: Get financial summary

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License
