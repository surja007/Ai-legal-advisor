# Ai-legal-advisor
A web-based legal assistance application that provides document analysis, case predictions, and a legal chat assistant. Built with Python, Flask, and modern NLP technologies.

## Features

- **Document Analysis**: Upload and analyze legal documents
- **Case Prediction**: Get predictions for legal cases
- **Legal Chat Assistant**: Interactive chat for legal queries
- **RESTful API**: Easy integration with other services

## Prerequisites

- Python 3.8+
- pip (Python package manager)
- Virtual environment (recommended)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Legal-Advisor
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Download required NLP models:
   ```bash
   python -m spacy download en_core_web_sm
   python -m nltk.downloader punkt
   ```

## Running the Application

1. Start the backend server:
   ```bash
   python run.py
   ```

2. The application will be available at: http://localhost:5000

## API Endpoints

- `GET /test` - Test endpoint
- `GET /api/health` - Health check
- `POST /api/analyze-document` - Analyze legal documents
- `POST /api/predict-case` - Get case predictions
- `POST /api/chat` - Legal chat assistant

## Project Structure

```
Legal-Advisor/
├── backend/           # Backend Flask application
├── frontend/          # Frontend code
├── models/            # ML models
├── static/            # Static files
├── templates/         # HTML templates
├── tests/             # Test files
├── requirements.txt   # Python dependencies
└── run.py             # Main application entry point
```

## Development

To run tests:
```bash
pytest
```

To check test coverage:
```bash
pytest --cov=.
```

## Troubleshooting

- If you encounter dependency issues, ensure you're using the exact versions specified in `requirements.txt`
- Check `legal_advisor.log` for application logs
- For Flask-related issues, refer to `flask_startup.log`

## License

## Contact

surjagaming0@gmail.com
