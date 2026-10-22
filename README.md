# 🕒 Time-Pilot — AI Timetable Assistant

**Generate. Optimize. Edit.**

Time-Pilot is an AI-powered timetable generation and editing web application designed to help teachers and educational institutions create, customize, and manage school and college timetables more efficiently.

## 📌 Project Overview

Creating an effective timetable requires balancing subjects, teachers, class durations, working days, and break times. Time-Pilot simplifies this process by combining AI-assisted timetable generation with interactive editing tools.

Users can describe their timetable requirements, generate a schedule, modify it manually or through natural-language instructions, and export or share the final timetable.

## ❗ Problem

Creating school and college timetables manually can be time-consuming and difficult.

- Balancing subjects and periods across working days takes effort.
- Teacher schedules and break times can create conflicts.
- Last-minute changes require repeated manual adjustments.
- Sharing and distributing updated timetables can be inconvenient.
- Traditional timetable tools may lack flexible AI-assisted editing.

## 💡 Solution

Time-Pilot provides an interactive timetable assistant that helps users generate and modify schedules using AI.

Users enter their timetable requirements, including subjects, teachers, working days, school timings, break periods, and class duration. The application helps generate a timetable and provides tools to adjust timings, rearrange subjects, validate changes, and share or download the result.

The application uses a frontend-only architecture and does not require a dedicated backend server or database.

## ✨ Features

- 🤖 **AI-Powered Timetable Generation** — Generate timetables from user-provided requirements with Google Gemini.
- 💬 **Natural-Language Editing** — Request timetable changes using conversational instructions.
- 📅 **Interactive Timetable Grid** — View and organize subjects across working days and periods.
- 🖱️ **Drag-and-Drop Editing** — Rearrange timetable entries interactively.
- ⏰ **Dynamic Time Adjustment** — Modify school timings, break times, and class duration.
- ✅ **Timetable Validation** — Check for scheduling conflicts and invalid changes.
- ↩️ **Undo and Redo** — Reverse or restore recent timetable edits.
- 📄 **PDF Export** — Download a formatted timetable as a PDF.
- 🔗 **Shareable Timetable Links** — Share timetable data through an encoded URL.
- 🌙 **Dark Mode** — Switch between light and dark themes.
- 📱 **Responsive Interface** — Designed to work across mobile and desktop screen sizes.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React | Building the user interface |
| JavaScript (ES6+) | Application logic |
| Vite | Development server and build tooling |
| Tailwind CSS | Styling and responsive layouts |
| Google Gemini API | AI-assisted generation and editing |
| React Router | Client-side navigation |
| dnd-kit | Drag-and-drop interactions |
| jsPDF | PDF generation |
| jspdf-autotable | Rendering timetable tables in PDFs |
| LZ-String | Compressing timetable data for shareable links |
| Lucide React | Icons |



## 🚀 How to Use

1. Open Time-Pilot in your browser.
2. Start the timetable assistant.
3. Enter your subjects, teacher assignments, working days, school timings, break times, and class duration.
4. Generate the timetable.
5. Review and modify the schedule using drag-and-drop or AI-assisted editing.
6. Adjust timings and review any validation messages.
7. Download the timetable as a PDF or generate a shareable link.

## 🏗️ Architecture

Time-Pilot follows a frontend-only architecture.

- **User interface:** React and Tailwind CSS.
- **AI integration:** Google Gemini API for interpreting timetable requirements and editing instructions.
- **Scheduling and validation:** Client-side JavaScript logic.
- **Timetable sharing:** URL encoding and compression.
- **PDF generation:** jsPDF and jspdf-autotable.
- **Data handling:** Browser-side application state, with optional local storage.

No dedicated application backend or database is required by the documented architecture. AI functionality requires an internet connection.

## 🔮 Future Improvements

Potential future enhancements include:

- Managing multiple saved timetables.
- Teacher-wise timetable views.
- Classroom and room allocation.
- Excel and CSV export.
- Multi-language support.
- More flexible timetable sharing and collaboration.

## 🎯 Project Goal

The goal of Time-Pilot is to make timetable creation easier, more flexible, and less time-consuming through AI assistance and interactive scheduling tools.

---

**Built with React, JavaScript, and Google Gemini.**
