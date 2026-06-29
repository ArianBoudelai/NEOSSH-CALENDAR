# NEOSSH CALENDAR
Another unique piece of NEOSSH project, (Cyberpunk themed Calendar)

The clock system updates every second using Date() API.

The calendar engine dynamically generates months and handles navigation.

Events are stored locally using:

localStorage.setItem("neossh_events", JSON.stringify(events))

Clicking a date opens a modal editor for adding notes or reminders.
Saving an event triggers a firework animation effect 🎆
Canvas-based particle system powers the visual effects.

Built With
HTML5
CSS3 (Glassmorphism + Neon UI)
Vanilla JavaScript (No frameworks)
Canvas API (Fireworks system)
LocalStorage API

Interaction
Click any date → Add / edit event
Click anywhere on background → Firework explosion 💥
Use arrows → Navigate months
Press Today → Jump to current date

NEOSSH CALENDAR is designed as a futuristic time-management interface for a cyberpunk world (2077 aesthetic).
It blends utility with visual storytelling, turning a simple calendar into an immersive experience.

Notes
No backend required
Fully offline capable
All data stored in browser memory (LocalStorage)


This project can be extended into:

Task manager system
AI planner assistant
Cloud-synced calendar
Desktop app (Electron)
