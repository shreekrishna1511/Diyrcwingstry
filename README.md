# DIYRCWings Clone

A simple web app to generate NACA 4-digit airfoil wing shapes and corresponding G-code for CNC cutting.

## Features

- Input NACA 4-digit airfoil code (e.g. 0012, 2412)
- Set chord length (mm)
- Set number of points for accuracy
- Preview wing shape in 2D SVG
- Download G-code file for CNC machines

## Tech stack

- Backend: Python Flask + NumPy
- Frontend: React.js

## Setup

### Backend

```bash
cd backend
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

Backend runs on `http://localhost:5000`

### Frontend

```bash
cd frontend
npm install
npm start
```

Frontend runs on `http://localhost:3000` and proxies API requests to backend.

## Usage

Open frontend in browser, enter airfoil parameters, click **Generate Wing & G-code**, see preview, download file.

---

Feel free to improve and customize!
