# ScalePilot AI

**Predictive Auto-Scaling of Cloud Applications Using Machine Learning**

Built using Flask, Python, Scikit-learn, SQLite, and Chart.js.

## Folder Structure

```text
scalepilot-ai/
├── app.py
├── templates/
│   └── index.html
├── requirements.txt
├── test_app.py
├── Dockerfile
├── .gitignore
└── README.md
```

## Run on Windows (PowerShell / CMD)

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python test_app.py
python app.py
```

Open your browser and visit:

http://127.0.0.1:5000

## Optional: Run Using Docker

```bash
docker build -t scalepilot-ai .
docker run -p 5000:5000 scalepilot-ai
```