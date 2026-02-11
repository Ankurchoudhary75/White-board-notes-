🖊 White Board Web Application

A fully functional browser-based Whiteboard application built using HTML, CSS, and JavaScript.

This application allows users to draw freely, erase, undo/redo strokes, add sticky notes, upload images, and download the canvas as an image.

🚀 Features
✏ Drawing Tool

Adjustable pen size (1px – 40px)

Multiple color options (Black, Yellow, Blue, Green, Red)

Smooth drawing using Canvas API

🧽 Eraser Tool

Adjustable eraser size

Switch between pen and eraser seamlessly

🔄 Undo & Redo

Undo last stroke

Redo previously undone stroke

Maintains drawing history using arrays

📝 Sticky Notes

Add editable sticky notes

Drag and move notes

Minimize / Expand notes

Close and remove notes

🖼 Image Upload

Upload image from local system

Image appears inside draggable sticky

Resize automatically inside container

⬇ Download Canvas

Download current whiteboard as JPG image

📱 Responsive Canvas

Canvas resizes automatically on window resize

Previously drawn lines are restored

🏗 Project Structure
WhiteBoard/
│
├── index.html
├── style.css
├── script.js
└── icons/

🛠 Technologies Used

HTML5

CSS3

JavaScript (Vanilla JS)

HTML5 Canvas API

📂 File Explanation
1️⃣ index.html

Contains:

Toolbar (pen, eraser, undo, redo, sticky, upload, download)

Canvas element for drawing

Tool options dropdowns

2️⃣ style.css

Handles:

Toolbar styling

Sticky note design

Tool option popups

Responsive layout

Visual effects (fade, active tool, shadows)

3️⃣ script.js

Main logic file containing:

Canvas drawing events (mousedown, mousemove, mouseup)

Line storage system (linesDB, redoLinesDB)

Pen & eraser functionality

Sticky note creation & drag system

Image upload handling

Undo/Redo system

Canvas download feature

🧠 How It Works
Drawing System

On mousedown: start new line

On mousemove: draw line segments

On mouseup: save line into database

All strokes stored inside linesDB

Undo / Redo Logic

Undo → removes last line from linesDB and pushes to redoLinesDB

Redo → restores last undone line

Canvas redraws from stored database

Sticky Notes

Created dynamically using DOM

Draggable using mouse event listeners

Supports text or image content

▶ How to Run the Project

Download or clone the repository

Open folder

Double-click index.html

Start drawing 🎉

No server required. Runs directly in browser.

📌 Future Improvements (Optional Enhancements)

Add shape drawing (rectangle, circle, line)

Add text tool on canvas

Add background grid

Add save to localStorage

Add real-time collaboration using WebSockets

Add dark mode

📸 Application Preview

Toolbar at top

Full-screen drawing area

Floating sticky notes

Image upload inside draggable container

👨‍💻 Author

Ankur Choudhary
GitHub: @Ankurchoudhary75

Frontend Developer | JavaScript Enthusiast | Problem Solver

This project showcases practical implementation of:

HTML5 Canvas API

Dynamic DOM manipulation

Event-driven architecture

Undo/Redo state management

Draggable UI components

Image handling & canvas export

Built with focus on clean structure, maintainability, and interactive user experience.
