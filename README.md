# 2048 Game (Flask + JavaScript)

A web-based implementation of the popular **2048 puzzle game**, built using **Flask (Python)** for backend game logic and **JavaScript** for rendering the UI.  

---

## 🎮 Features
- Classic **2048 gameplay**.
- Responsive UI styled with CSS.
- **Flask API endpoints** to handle game state and moves.
- Keyboard controls (Arrow keys).
- Score tracking.
- "New Game" button to restart.

---

## 🗂 Project Structure
```
.
├── app.py            # Flask backend server
├── game_logic.py     # Core game logic (board state, moves, merges)
├── templates/
│   └── index.html    # Main HTML page
├── static/
│   ├── style.css     # Styling for the game
│   └── game.js       # Frontend logic (UI updates, API calls)
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd <repo-folder>
```

### 2. Create and activate a virtual environment (recommended)
```bash
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
```

### 3. Install dependencies
```bash
pip install flask
```

### 4. Run the Flask app
```bash
python app.py
```

By default, the app runs on:
```
http://127.0.0.1:5000/
```

If you want to access it from other devices in your network, use:
```
http://<your-local-ip>:5000/
```

---

## 🎮 How to Play
1. Open the game in your browser.
2. Use **Arrow keys** to move the tiles.
3. When two tiles with the same number touch, they merge.
4. Try to reach the **2048 tile** (or go beyond!).



## 🛠 Tech Stack
- **Backend**: Python, Flask  
- **Frontend**: HTML, CSS, JavaScript  
- **Game Logic**: Python (`game_logic.py`)  

---


