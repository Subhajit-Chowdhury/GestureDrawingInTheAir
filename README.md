# Gesture Drawing in the Air — AI Spatial Interface

Draw, move, and create in the air using just your hands — no pen, no paper, just your fingers!

This is a smart web app that uses your webcam to track your hand movements. Think of it like a digital canvas floating in front of you. You draw with one hand and control your drawings with the other — like something out of a sci-fi movie!

---

## What Can You Do?

### ✋ Draw with Your Right Hand
- **Point your index finger up** → Start drawing
- **Pinch your thumb and finger** → Erase parts of your drawing
- **Make a fist** → Clear everything and start fresh

### 🖐️ Control with Your Left Hand
- **Show two fingers** → Grab and move your drawing
- **Pinch and spread fingers** → Make your drawing bigger or smaller
- **Open your palm** → Rotate your drawing around

---

## How It Works (Simple Explanation)

### Step 1: The Camera Watches You
The app turns on your webcam. It looks for your hands and follows every finger movement in real-time.

### Step 2: Your Right Hand Draws
When you raise your index finger, the app starts recording your movement. Wherever your finger goes, a glowing line follows — like a magical pen in the air!

### Step 3: Your Left Hand Controls
Want to move what you drew? Use your left hand. Show two fingers near your drawing, then move your hand — the drawing follows! Pinch and spread to resize. Open your palm to spin it around.

### Step 4: Smart Rendering
All your strokes are saved as points. When you move, scale, or rotate something, the app calculates the new position instantly. Your original drawing stays safe — nothing gets permanently changed!

---

## Why This Is Cool?

- **No tools needed** — Just your hands
- **Non-destructive** — Your original strokes never get ruined
- **Smooth feel** — Movements have natural inertia, like sliding on ice
- **Snap angles** — Rotation snaps to 45° angles for perfect alignment
- **Beautiful design** — Glassmorphism UI with neon glow effects
- **Fast** — Runs at 60 frames per second

---

## 🔧 What Powers This App?

| Technology | What It Does |
|------------|---------------|
| React + Vite | Makes the app fast and responsive |
| MediaPipe Hands | Tracks your hand and finger positions |
| Framer Motion | Adds smooth animations |
| Lucide React | Provides nice icons |
| Vanilla CSS | Creates the glassmorphism look |

---

## 🎮 Complete Gesture Guide

### Right Hand (Drawing)

| Hand Shape | Action |
|------------|--------|
| ☝️ Index finger up | Start a new stroke |
| 🤏 Pinch (thumb + index) | Erase where your finger touches |
| ✊ Fist | Delete everything |

### Left Hand (Controlling)

| Hand Shape | Action | What You See |
|------------|--------|---------------|
| ✌️ Two fingers | Move a stroke | Blue glow appears |
| 🤏 Pinch + spread | Scale (resize) | Rings show the size |
| 🤚 Open palm | Rotate | Orange arc appears |

---

## 🚀 How to Run This

### Step 1: Get the Code Ready
Open your terminal or command prompt and type:

```bash
npm install
```

This downloads all the required tools and libraries.

### Step 2: Start the App
After installation completes, type:

```bash
npm run dev
```

Wait a few seconds. You should see a local web address (like `http://localhost:5173`).

### Step 3: Use It!
1. Open the link in your browser
2. Allow camera access when asked
3. Stand back so your hands are visible
4. Start drawing!

---

## 💡 Tips for Best Experience

- **Good lighting** — Make sure your face and hands are well-lit
- **Face the camera** — Sit or stand so your hands are clearly visible
- **Background matters** — A plain wall works better than a busy room
- **Practice** — It takes a minute to get used to. Try each gesture slowly!

---

## 👨‍💻 Created By

**Subhajit Chowdhury**

🐙 GitHub: [Subhajit-Chowdhury](https://github.com/Subhajit-Chowdhury)

---

*Crafted with cosmic passion for AI and Spatial Computing — By Subhajit Chowdhury.*