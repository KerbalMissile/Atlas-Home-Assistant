# Atlas - Open Source Home Assistant Web App

Atlas is a home assistant project that runs on your PC and Raspberry Pi. It is built with Python (FastAPI) for the backend and a web app frontend. The goal is to make a private and customizable assistant that you control.

## Features

- Runs locally for privacy
- Python backend with FastAPI
- Web app frontend with modern JavaScript
- Real-time communication with WebSockets
- Modular design to add device support
- Works well on Raspberry Pi

## Project Structure

```
Atlas/
├── backend/            # Python backend (FastAPI)
├── frontend/           # Web app frontend
│   ├── assets/         # Logos, icons, and images
│   ├── src/            # Source code
│   └── public/         # Static files
├── docs/               # Documentation and notes
├── CONTRIBUTING.md     # How to help
├── LICENSE.md          # License info
└── README.md           # This file
```

## Getting Started

### Backend Setup

1. Clone the repo:

```bash
git clone https://github.com/KerbalMissile/atlas.git
cd atlas/backend
```

2. Make and activate a virtual environment:

```bash
python -m venv venv
# Windows
.\venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
```

3. Install needed packages:

```bash
pip install fastapi uvicorn python-socketio
```

4. Run the backend server:

```bash
python main.py
```

Open your browser to `http://127.0.0.1:8000` to check if it works.

## Frontend Setup

- Use any modern frontend framework like React or Vue, or plain JavaScript.
- Use WebSockets or Socket.IO to talk to the backend.
- Put images and logos in `frontend/assets/`. SVG is best.

## Contributing

You can help! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before sending issues or pull requests.

## License

This project uses the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License. See [LICENSE.md](LICENSE.md) for details.

## Contact

Made by KerbalMissile. Reach out on GitHub if you want.