# Bloom Wellness Tracker

Bloom Wellness Tracker is a gamified, interactive web application that helps users track their mental wellness journey through the metaphor of growing flowers. Complete tasks, track your mood, journal, and practice breathing exercises to grow a virtual garden of flowers.

---

## Features

### Flower Growth System
- Start each day with a seedling.
- Complete 5 tasks to earn petals.
- Collect 5 petals to bloom a flower and add it to your garden.
- Visual flower animations show your progress.
- Each flower has a consistent color theme for all petals.

### Task Management
- Add custom daily tasks with categories: Mind, Body, Emotional, Productivity.
- Suggested tasks for inspiration.
- Mark tasks as completed with checkboxes.
- Daily progress bar shows task completion.

### Mood Tracking
- Six mood options with color-coded labels.
- Track daily mood trends and gain insights over time.

### Breathing Exercises
- Guided 4-7-8 breathing technique (inhale-hold-exhale).
- Animated breathing circle with timer and instructions.

### Daily Journal
- Random daily prompts for reflection.
- Save entries with date and mood tags.
- View past journal entries and trends.

### Flower Garden
- Collection of all completed flowers.
- Each flower shows unique color and creation date.
- Click to view detailed statistics.

### Progress Statistics
- Day counter and streak tracking.
- Total petals earned and tasks completed.

### User Management
- Local user accounts with persistent storage.
- Secure login/signup system.
- Individual progress saved per user.

---

## Getting Started

### Prerequisites
- No installation required.
- Works in any modern web browser.

### Usage
1. Open `index.html` in a browser.
2. Create an account or log in.
3. Start tracking your wellness journey and grow your garden.

---

## Architecture

### Frontend
- **HTML5**: Semantic structure  
- **CSS3**: Custom variables, responsive design, animations  
- **Vanilla JavaScript**: No frameworks required  

### Data Storage
- **Local Storage**: All user data persists locally  
- **Offline Ready**: Fully functional without internet  

### Key Components
- `UserManager` class handles authentication and user state.
- App state management for tasks, flowers, and journal entries.
- Interactive UI with real-time updates and visual feedback.

---

## Design Principles

- **Color Palette**  
  - Primary: Purple (#9c88ff)  
  - Secondary: Pink (#ff9ff3), Blue (#54a0ff)  
  - Success: Green (#1dd1a1)  
  - Background: Soft gradient for calm experience  

- **Responsive Design**  
  - Mobile-first, touch-friendly, works on all screen sizes  

- **Animations**  
  - Smooth transitions, task completion effects, flower progress animations  

---

## PWA Features
- Installable as a Progressive Web App
- Consistent theme and responsive on all devices

---

## Technical Details

- **Data Structure:** Encrypted user data, tasks linked to specific days, flowers track petal colors and dates, journal entries tagged with mood.
- **Key Functions:**  
  - `createNewFlower()`: Generate a new flower  
  - `addPetalToFlower()`: Add petals and trigger celebrations  
  - `checkStreak()`: Calculate activity streaks  
  - `updateUI()`: Sync UI with current state  

- **Customization:**  
  - Add new task categories, moods, flower colors, journal prompts via arrays in JavaScript  
  - Modify CSS variables for colors, breakpoints, and animation effects  

---

## Testing & Compatibility

- **Browsers Supported:** Chrome 60+, Firefox 55+, Safari 12+, Edge 79+  
- **Offline Capabilities:** Fully functional after initial load  
- **Tips:** Clear browser cache if login issues occur

---

## Contributing

- Fork the repository  
- Create a feature branch  
- Make improvements  
- Submit a pull request  

---

## Acknowledgments
- Icons: Font Awesome  
- Color palette: Inspired by nature and wellness  
- Breathing exercises: 4-7-8 technique  
- Design: Positive psychology and gamification principles  

---

## License
Personal and educational use. Modify as needed for your wellness tracking.

---

Bloom Wellness Tracker makes self-care interactive, rewarding, and visually engaging. Start growing your wellness garden today.
