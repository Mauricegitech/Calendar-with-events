Calendar with Events
A simple, responsive calendar web app built with vanilla JavaScript, HTML, and CSS. Supports month/year navigation, event markers, adding/editing/deleting events, keyboard shortcuts, and local persistence via localStorage.
Overview
Purpose Provide a lightweight, easy-to-embed calendar component for personal projects and prototypes. Designed to be readable, accessible, and simple to extend (tooltips, external storage, recurring events).
Key design goals
•	Clear visual hierarchy and responsive layout
•	Minimal dependencies (only Font Awesome for icons and Google Fonts for typography)
•	Immediate feedback: events show as markers and open a modal with details
Features
•	Month and year navigation with Prev/Next controls
•	Today shortcut to jump to the current date
•	Event markers (small dots) on days that have events
•	Add Event modal with date and title inputs
•	View, edit, delete events for a selected day
•	Keyboard shortcuts: arrow keys for navigation, t for today, a to open Add Event
•	Persistence using localStorage so events survive page reloads
•	Accessible controls: focusable day cells, ARIA labels, keyboard activation
Install and Run
Requirements
•	Modern browser (Edge, Chrome, Firefox, Safari)
•	No build step required
Quick start
1.	Save the provided HTML, CSS and JAVASCRIPT file as index.html, styles.css ad script.js.
2.	Open your files in your browser (double-click or serve from a local server).
3.	The calendar renders immediately and stores events in localStorage.
Optional local server
•	Use a simple static server if you prefer:
Usage and Adding Events
Add an event
•	Click Add Event, choose a date, enter a title, and click Save. The day will show an event marker immediately.
View events for a day
•	Click a day cell to open the modal listing events for that date. From there you can edit or delete events.
Edit an event
•	In the day events view, click the edit icon to populate the Add/Edit form. Save to update.
Delete an event
•	In the day events view, click the trash icon next to the event to remove it.
Data format
•	Events are stored as objects:
js
{ date: "YYYY-MM-DD", title: "Event Title" }
•	All events are saved to localStorage under the key calendarEvents.

Clone or download the project.:
git clone https://github.com/Mauricegitech/Calendar-with-events.git

📜 License This project is licensed under the MIT License — open, collaborative, and community‑friendly.

👨‍💻 Author Created by Maurice Githinji (Mauricegitech)
Github 
https://github.com/Mauricegitech
