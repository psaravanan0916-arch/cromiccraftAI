# Phase 5 – Project Development

## Project Structure

```text
app/
├── main.py
├── routes.py
├── gemini_flash.py
├── gemini_pro.py
├── image_generator.py
├── layout_builder.py
└── exporters.py

templates/
├── index.html
├── comic_preview.html
└── export_success.html

static/
├── panels/
└── exports/

requirements.txt
.env.example
```

## Core Modules

### Gemini Flash – `gemini_flash.py`
Generates a structured 5-panel comic outline.

### Gemini Pro – `gemini_pro.py`
Generates detailed narration and character dialogues.

### Image Generator – `image_generator.py`
Uses Stable Diffusion to generate comic-style illustrations.

### Layout Builder – `layout_builder.py`
Organizes generated images and story content into a comic layout.

### PDF Exporter – `exporters.py`
Compiles the comic into a multi-page PDF using FPDF.

## Running the Application

```bash
python -m venv env
env\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Application:
`http://127.0.0.1:8000`

API documentation:
`http://127.0.0.1:8000/docs`

## Security
Do not upload real API keys. Use `.env.example` for placeholder environment variables.
