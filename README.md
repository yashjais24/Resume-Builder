# Resume Builder

This project is a resume builder application with a FastAPI backend and a React + Vite frontend. It supports AI-driven resume generation, PDF creation, and a responsive UI for building and previewing resumes.

## Project Structure

### Backend
- Built with FastAPI
- `main.py` → backend server entry point
- `routes/` → API endpoints for AI integration and PDF generation
- `templates/` → HTML templates used for resume generation
- `utils/` → core AI and PDF helper logic
- `requirements.txt` → backend Python dependencies
- `render.yaml` → deployment configuration for Render

### Frontend
- Built with React and Vite
- `src/App.jsx` → root component and routing setup
- `src/components/` → reusable UI components for resume creation
- `src/components/image/ImageWithFallback.jsx` → image fallback handling
- `src/components/ui/` → shared UI primitives and controls
- `src/pages/` → main page layouts such as home and preview
- `src/services/ai.js` → AI-related frontend service
- `src/services/api.js` → backend API integration
- `src/index.css` → base frontend styles
- `src/styles/global.css` → global application styles
- `index.html` → HTML entry point for the Vite app

## Contributors

### Yash Jaiswal || 2400520100078
- Backend architecture and FastAPI setup
- Implemented routing for AI and PDF endpoints
- Managed HTML template flow for resume generation

### Krrish Verma || 2400520100045
- Developed core backend logic in `utils/`
- Set up backend dependency management in `requirements.txt`
- Created deployment config in `render.yaml`

### Megha Verma || 2400520100051
- Built React frontend structure and page layouts
- Implemented reusable components in `src/components/`
- Managed root app routing and layout in `src/App.jsx`
- Established frontend entrypoint via `index.html`

### Vidushi Pandey || 2400520100074
- Designed and implemented the `Header`, `HomePage`, and `PreviewPage` React components
- Established the frontend component organization and project structure
- Developed responsive styling in `src/index.css` and `src/styles/global.css`
- Integrated navigation and preview workflows for the resume UI
- Ensured consistent visual design and layout across frontend pages

## Notes
- The backend and frontend are separated in `backend/` and `frontend/` folders respectively.
- Frontend services connect to backend APIs for AI and resume generation features.
- UI primitives in `src/components/ui/` support consistent styling and reusable behavior.

