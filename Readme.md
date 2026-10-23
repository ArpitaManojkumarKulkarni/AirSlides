# ✋🖥️ AirSlides: Hand Gesture Presentation System

**AirSlides** is a real-time slide controller using hand gesture recognition powered by **MediaPipe** and **OpenCV**. Navigate, point, draw, and clear your presentation slides — all hands-free!

---

## 🚀 Features

- **Next Slide**: Open palm  
- **Previous Slide**: Thumbs-up  
- **Pointer Mode**: L-sign (index + thumb)  
- **Draw Mode**: Pointing (index finger)  
- **Clear / Undo**: “C” sign (open claw)  

---

## ✋ Gesture-to-Feature Mapping

| Label | Gesture                | Visual Description                             | Trigger               |
|:-----:|:-----------------------|:-----------------------------------------------|:----------------------|
| 0     | **Palm**               | All five fingers spread, palm facing forward   | Next Slide            |
| 1     | **L Sign**             | Index finger up, thumb out, other fingers folded | Pointer Mode         |
| 2     | **Thumb Up**           | Only thumb raised, others curled (like 👍)      | Previous Slide        |
| 3     | **Index Finger Up**    | Only index raised, pointing gesture            | Draw Mode             |
| 4     | **C Sign** (Open Claw) | Hand curved like a “C” or holding a ball       | Clear Drawing / Undo  |

---

## 🛠️ Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/ArpitaManojkumarKulkarni/AirSlides.git
cd AirSlides

# 2. Create a Python virtual environment
python3 -m venv venv

# 3. Activate the environment
# macOS / Linux:
source venv/bin/activate
# Windows PowerShell:
# venv\Scripts\activate

# 4. Install dependencies
pip install -r requirements.txt
```

## Project Contributors

AirSlides was developed as a collaborative academic project by:

- Arpita Manojkumar Kulkarni
- Khushi Saxena
- Rucha Dave

This repository contains the shared project implementation and preserves its original development history.
