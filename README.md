🗂️ KanbanPro
A clean, fully-featured Kanban task management dashboard built with zero dependencies — just a single HTML file using vanilla JavaScript, CSS variables and Tailwind CSS via CDN.

✨ Features

Multi-project support — create unlimited projects, each with their own task board
Drag & drop — move tasks between columns using native HTML5 drag-and-drop (no libraries)
Three columns — Yet to Start / In Progress / Completed
Task management — add, edit, delete tasks with title, description, priority, and column
Priority badges — Low (green), Medium (yellow), High (red)
Live progress ring — SVG circular progress showing completion %
Stats sidebar — real-time task counts per column
Search — filter tasks by title or description instantly
Dark / Light mode — toggle with memory across sessions
Persistent storage — all data saved in localStorage, survives page refresh
Responsive — columns stack vertically on mobile
Keyboard shortcuts — Enter to save modal, Escape to close

-->Getting Started
No build step. No install. Just open the file.
bash# Clone the repo
git clone https://github.com/shamaimmalikofc/kanbanflow.git
cd kanbanflow

📁 Project Structure
kanbanflow/
└── index.html      # Entire app — HTML + CSS + JS in one file
└── README.md       # This file
That's it. One file contains everything:
SectionWhat's inside<head>Tailwind CDN, Google Fonts (Plus Jakarta Sans)<style>CSS variables, layout, component styles<body>Navbar, board columns, sidebar, modals<script>All app logic — state, render, drag/drop, modals

🧰 Tech Stack
TechWhyVanilla JS (ES2020)No framework overhead, runs anywhereCSS Custom PropertiesInstant theme switching without re-renderingTailwind CSS (CDN)Utility classes for rapid layoutPlus Jakarta SansClean, modern, readable typefaceHTML5 Drag & Drop APINative browser drag, no library neededlocalStorageZero-config persistence

🐛 Known Limitations

No real-time collaboration (single browser, single user)
No undo/redo
localStorage has a ~5MB limit (more than enough for thousands of tasks)
Drag ghost image appearance varies slightly between browsers (Chrome vs Firefox vs Safari)


