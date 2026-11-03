# MP2 REST API

This project is a REST API built with Python and FastAPI that allows users to upload, retrieve, and process CSV datasets. It connects the data-cleaning functions from MP1 to an API, allowing users to validate data, remove duplicates, handle missing values, and optionally remove outliers. The application also includes request logging, error handling, and automated tests.

## Running the API

Install dependencies:

```bash
pip install -r requirements.txt
```

Start the server:

```bash
python -m uvicorn main:app --reload
```

Open `http://127.0.0.1:8000/docs` to test the API.

## Running Tests

```bash
python -m pytest tests -v
```