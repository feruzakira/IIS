### Setup

```bash
cd 7/
python3 -m venv venv --system-site-packages
source venv/bin/activate # Depends on your system
pip install -r requirements.txt
uvicorn app.main:app --reload
```

### Tests

```bash
python3 -m pytest
```

### Run interface

```bash
streamlit run 7/front/ui.py
```
