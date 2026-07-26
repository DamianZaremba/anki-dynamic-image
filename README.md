Anki Dynamic Image Template
============================

Card template for Anki for scenarios rendered as a small dot-diagram (e.g. a set of navigation
lights) paired with several category questions about it.

Features:
- A dynamically drawn "board" of points (stored as a JSON `Board` field: `{"gridIsBlack": bool, "points": [{"x": 0-1, "y": 0-1, "color": "#hex"}, ...]}`)
- Any number of category questions, each with a dropdown of options (stored as a JSON `Categories` field: `[{"label": ..., "options": [...], "correct": ...}, ...]`)
- Front side lets you pick an answer per category; back side marks each correct/wrong

# Installation

There are 2 options for installation:

1. Clone this repo and execute scripts/sync-database.py (will update an existing entry)
2. Import the dynamic-image.apkg file from a release
