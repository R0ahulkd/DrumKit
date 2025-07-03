🥁 Drum Kit – Interactive Sound Project

A mini project built using HTML, CSS & JavaScript to play drum sounds through button clicks or keyboard presses.

📌 Project Overview

This Drum Kit Web App is a fun and interactive project created to practice core JavaScript skills such as:

Event listeners

DOM manipulation

Audio playback

Keyboard input handling

Dynamic class toggling for animations

Users can either click on the on-screen drum buttons or press the respective keys on the keyboard (w, a, s, d, j, k, l) to hear different drum sounds and see a short animation effect.

🎯 This project is created as a practice exercise to enhance my understanding of front-end development, not intended for real-world usage.

🧠 Key Concepts Practiced

querySelectorAll() and dynamic loop-based event binding

addEventListener() for both mouse clicks and keyboard inputs

Audio() constructor for playing .mp3 files

Using switch statements for mapping input to actions

CSS class manipulation (classList.add/remove) for button animation

Timing effects with setTimeout()

🛠️ Technologies Used

✅ HTML5 – For structuring the drum buttons and layout

✅ CSS3 – For styling and pressed-button animation

✅ JavaScript (Vanilla) – For interactive behavior and sound control

✅ Google Fonts – Custom font (Arvo) for header styling

📂 File Structure

bash
Copy
Edit

📁 Drum-Kit
├── 📄 index.html         # Main HTML structure
├── 📄 styles.css         # Button styling & animation
├── 📄 index.js           # JavaScript for sound and interactivity
└── 📁 sounds             # Drum sound files
    ├── tom-1.mp3
    ├── tom-2.mp3
    ├── tom-3.mp3
    ├── tom-4.mp3
    ├── snare.mp3
    ├── crash.mp3
    └── kick-bass.mp3
    
⚙️ How It Works

The page loads a set of drum buttons labeled with characters w, a, s, d, j, k, l.

When a user clicks a button or presses the corresponding keyboard key:

A matching .mp3 sound plays.

The button is briefly animated using a CSS .pressed class.

After 100ms, the animation class is removed, giving a visual "press" effect.

👨‍💻 My Role

I independently developed this project to:

Strengthen my DOM manipulation skills

Understand event-based interactions in JavaScript

Learn how to play sound files using JS

Build a responsive, keyboard-driven interface

🎯 Project Goal

“Not a commercial or production-grade app — this is purely for JavaScript practice and learning frontend sound interactivity.”

📸 Demo Screenshot
![{3F9ACF1C-7BB0-4C8D-8755-AB668F61BC86}](https://github.com/user-attachments/assets/715d3f7c-3d2d-485b-a783-88369cbf638f)
