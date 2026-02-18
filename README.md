📌 About
This project transforms a traditionally dry Computer Science topic — memory management — into an engaging, interactive learning experience. It's designed for beginners and self-learners who want to think like engineers, not just memorize definitions.

Inspired by a lecture covering memory management concepts in JavaScript and systems programming, this explainer breaks down everything with real analogies, live demos, and a quiz.

🌐 Live Demo
Deployed on Netlify: classy-cannoli-7d3268.netlify.app

Works on all devices — desktop, tablet, and mobile.

✨ Features
Feature	Description
🖥️ Interactive RAM Visualizer	Simulate Stack & Heap memory allocation in real-time
🧹 Garbage Collector Demo	Orphan variables and watch the GC sweep them away
⚙️ SMI Bit Encoder	Type a number and see how V8 encodes it directly in a pointer
🧪 Knowledge Quiz	4 questions with instant feedback and deep explanations
📱 Fully Responsive	Works on all screen sizes
🎨 Dark Theme UI	Clean, modern design with smooth animations
📚 What You'll Learn
The file covers 8 sections:

The Big Picture — SSD → RAM → CPU explained with analogies
Interactive RAM Demo — Play with simulated 32-byte memory
Stack vs Heap — The core difference, visually and logically
JavaScript in Action — What really happens when you write let name = "Rohit"
Garbage Collection — How JS automatically frees unused memory
SMI Optimization — The speed hack V8 uses for small integers
Knowledge Quiz — Test your understanding
Engineer's Mindset — How to think from first principles + learning roadmap
🚀 How to Run
Option 1 — Open Locally
Just double-click index.html — it opens directly in any browser. No setup needed.

Option 2 — Host on Netlify (recommended for sharing)
Rename the file to index.html
Go to app.netlify.com/drop
Drag and drop the file
Get a live URL instantly ✅
Option 3 — Local Network (share with phone on same WiFi)

bash
python -m http.server 8080
Then open http://YOUR_IP:8080/index.html on any device on the same network.

🗂️ File Structure

index.html        ← Everything in one file (HTML + CSS + JS)
README.md         ← This file
No build steps. No npm install. No dependencies. Just open and use.

🧩 Concepts Covered
RAM, SSD, CPU — and how they work together
Byte-addressable memory and address spaces
Stack memory — LIFO, fixed-size, fast
Heap memory — dynamic, flexible, managed
Pointers and references
JavaScript primitives and immutability
Garbage Collection — Mark & Sweep algorithm
SMI (Small Integer) optimization in V8
32-bit vs 64-bit address spaces
Engineering first-principles thinking
🛠️ Built With
Pure HTML5, CSS3, Vanilla JavaScript
Google Fonts: Syne, DM Mono, Lora
No external libraries or frameworks
