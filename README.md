# LegalEase

LegalEase is an AI-powered legal document drafting application.

It uses:

- Streamlit
- FastAPI
- Google Gemini
- Python
- python-docx
- fpdf2

## Features

- Employment contracts
- NDAs
- Lease agreements
- Freelance agreements
- Service agreements
- Partnership agreements
- General contracts
- AI-generated document drafts
- Editable document preview
- TXT export
- DOCX export
- PDF export
- Optional logo branding
- Multiple languages
- Jurisdiction field
- FastAPI backend
- Streamlit frontend

---

# Project Structure

LegalEase/

    main.py

    requirements.txt

    .env
    .env.example
    .gitignore

    backend/
        __init__.py
        routes.py
        schemas.py

        ai_core/
            __init__.py
            gemini_generator.py

        utils/
            __init__.py
            sanitize.py
            exporters.py

    frontend/
        app.py

    tests/
        __init__.py
        test_api.py

---

# Installation

## 1. Install Python

Use Python 3.10 or newer.

Check:

```bash
python --version