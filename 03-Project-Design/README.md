# Phase 3 – Project Design

## System Architecture

ComicCraft consists of:
1. Frontend (HTML, CSS, Jinja2)
2. Backend (FastAPI)
3. AI Integration (Google Gemini and Stable Diffusion)

## Architecture Flow

User
↓
Frontend
↓
FastAPI Backend
↓
Gemini Flash → Comic Outline
↓
Gemini Pro → Narration & Dialogue
↓
Stable Diffusion → Illustrations
↓
Layout Builder
↓
PDF Export

## Frontend
- `index.html` – user input
- `comic_preview.html` – generated comic preview
- `export_success.html` – export confirmation

## Backend
- Handles routing
- Processes user input
- Calls AI models
- Builds comic layout
- Exports PDF

## Main Routes
- `/`
- `/generate`
- `/generate-comic/json`
- `/test-image`
- `/export-success`

## Main Modules
- `routes.py`
- `gemini_flash.py`
- `gemini_pro.py`
- `image_generator.py`
- `layout_builder.py`
- `exporters.py`
