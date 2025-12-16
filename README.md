# Hello World v1 (Flask)

Simple Python web app that returns "Hello World v1".

## Setup

1. Create a virtual environment (optional but recommended):
   ```
   python -m venv .venv
   .\.venv\Scripts\activate
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Run

```
python app.py
```

Visit `http://localhost:8000/` to see the response.

## Run with Docker

Build the image:
```
docker build -t hello-world-v1 .
```

Run the container (maps host port 8000 to the container):
```
docker run -p 8000:8000 hello-world-v1
```

