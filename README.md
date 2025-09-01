# AI Chatbot (Flask)

A simple, fast chatbot UI (dark theme with typing indicator) + Flask backend calling OpenAI.

## Setup

1) Create a virtual environment (optional but recommended):
```
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate
```

2) Install dependencies:
```
pip install -r requirements.txt
```

3) Set your API key (recommended):
- Windows PowerShell:
```
setx OPENAI_API_KEY "sk-REPLACE_ME"
```
- Or edit `app.py` and replace `YOUR_API_KEY_HERE`.

4) Run:
```
python app.py
```
Open http://127.0.0.1:5000

## Notes
- Model: `gpt-4o-mini` for speed/cost. You can switch to another model.
- If you want to use a different provider (e.g., Mistral), replace the API call in `app.py` accordingly.
