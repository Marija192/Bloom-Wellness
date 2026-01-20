# Bloom Wellness Tracker

Bloom Wellness Tracker is an interactive front-end web application designed to support daily wellness habits through task management, mood tracking, journaling, breathing exercises, and a flower-based visual progress system.

The application uses the metaphor of growing flowers to encourage consistency and positive routines.

Live demo: https://marija192.github.io/Bloom-Wellness/

---

## Features

### Flower Growth System
- Start each day with a new seedling
- Complete five tasks to earn petals
- Collect five petals to fully bloom a flower
- Completed flowers are added to a personal garden
- Each flower has a consistent color theme and visual state

---

### Task Management
- Create custom daily tasks
- Task categories:
  - Mind
  - Body
  - Emotional
  - Productivity
- Suggested tasks for inspiration
- Mark tasks as completed
- Daily progress bar reflects task completion

---

### Mood Tracking
- Select one mood per day from predefined options
- Mood is saved locally and displayed in the interface

---

### Breathing Exercises
- Guided 4–5–7 breathing exercise
- Visual breathing animation with timer and instructions
- Start and reset controls

---

### Daily Journal
- Random daily prompts for reflection
- Save daily journal entries locally
- View past entries in a history modal

---

### Flower Garden
- Displays all completed flowers
- Flowers show visual state and completion order
- Clicking a flower opens a details view

---

### Progress Tracking
- Current day counter
- Daily streak tracking
- Total petals earned
- Total tasks completed

---

### User Management
- Local user accounts stored in the browser
- Login and signup functionality
- Individual progress saved per user using local storage

> Note: This is a front-end–only application. Authentication is not secure and passwords are stored in plain text for demonstration purposes only.

---

## Getting Started

### Prerequisites
- No installation required
- Runs in any modern web browser

### Usage
1. Open `index.html` in a browser
2. Create an account or log in
3. Begin tracking daily tasks and wellness activities

---

## Architecture

### Frontend
- **HTML5** – semantic page structure  
- **CSS3** – custom variables, responsive layout, animations  
- **Vanilla JavaScript** – no external frameworks  

### Data Storage
- **Browser LocalStorage**
- All application data is stored locally
- Fully functional offline after initial load

### Key Components
- `UserManager` class for handling users and application state
- Centralized app state for tasks, flowers, mood, and journal entries
- Dynamic UI updates based on user interaction

---

## Design Principles

### Visual Design
- Calm color palette with soft gradients
- Consistent spacing and rounded UI elements
- Clear visual feedback for progress and interaction

### Responsive Design
- Mobile-friendly layout
- Adaptable grid system for different screen sizes

### Animations
- Smooth transitions
- Visual feedback for task completion and flower growth

---

## Progressive Web App (PWA)
- Installable as a PWA
- Responsive across desktop and mobile devices
- Theme color and manifest configuration included

---

## Limitations
- No backend or database
- No encrypted authentication
- Data is lost if browser storage is cleared
- Intended as a demonstration and learning project

---

## Future Improvements
- Backend authentication and database support
- Secure password handling
- Cross-device data synchronization
- Mood and progress analytics
- Notifications and reminders

---

## Author

Marija  
Computer Science Student

---

## License

This project was created for educational and portfolio purposes.
