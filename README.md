# Cambridge IGCSE Computer Science (0478) Revision Portal

A lightweight, single-page revision web app covering the full Cambridge IGCSE Computer Science (0478) syllabus 
for both Paper 1 (Computer Systems) and Paper 2 (Algorithms, Programming & Logic).

---

## Features

### Comprehensive Syllabus Coverage
- **Paper 1 (Chapters 1–6):** Data Representation, Data Transmission, Hardware, Software, The Internet & Cyber Security, and Automated & Emerging Technologies.
- **Paper 2 (Chapters 7–10):** Algorithm Design & SDLC, Programming (Python & Cambridge pseudocode side-by-side), Single-table Databases (SQL), and Boolean Logic.
- **Visual Mind Maps:** Direct links to visual summary sheets for all 10 chapters hosted on Google Drive.

### Interactive Learning Tools
- **Hero Byte Explorer:** Toggle 8 bits interactively to inspect live Denary, Hexadecimal, and ASCII character conversions.
- **Base Converter (Chapter 1):** Real-time conversion across Denary (0–255), 8-bit Binary, and Hexadecimal.
- **Bubble Sort Visualizer (Chapter 7 & 8):** Step-by-step trace showing comparisons, swaps, and sorted elements on custom numeric lists.
- **Logic Gate Playground (Chapter 10):** Interactive input switches (A/B) driving live SVG outputs for NOT, AND, OR, NAND, NOR, and XOR gates.
- **Truth Table Generator (Chapter 10):** Automatically generates intermediate working columns and final outputs for standard syllabus Boolean expressions.

### Design & User Experience
- Zero external build dependencies (pure HTML5, CSS3, and vanilla JavaScript).
- Supports system default dark/light themes with manual toggle persistence via `localStorage`.
- Hash-based client-side routing (`#home`, `#p1/{ch}`, `#p2/{ch}`, `#mm`).
- Class access gate dialog using a client-side cyrb53 hash check.

---

## File Structure

```text
├── index.html        # Entire web application (UI, CSS styles, interactive logic)
└── README.md         # Documentation
