Focus & Study Time Tracker 🚀
A sleek, mobile-friendly web application designed to help students track study sessions, monitor daily class schedules with visual alerts, and log break reasons seamlessly. Built with vanilla HTML, CSS, and JavaScript, optimized for dark mode aesthetics.
🌟 Overview & Features
Dark Mode & Neon Design: Styled with a deep dark background and glowing purple bloom effects, perfectly tailored for late-night study sessions.
Smart Class Schedule Integration: Automatically checks your daily schedule and gives visual alerts for ongoing classes, remaining break times, and upcoming sessions.
Detailed Break Reason Logging: When ending an active session early, a custom modal pops up allowing you to select specific break reasons such as Smoking 🚬, Snacking 🍫, Lunch 🍲, or General Breaks 🕒.
Persistent Local Storage: Safely stores your subjects, accumulated durations, and history locally on your device without losing data.
Cross-Platform PWA Support: Fully functional on Android and iOS devices via browser deployment (GitHub Pages).


🛠️ Step-by-Step User Guide
Create or Continue a Subject:
Navigate to the Ders (Subject) tab.
Enter your Subject Name (required) and Topic (optional).
Click Sıfırdan Başla (Start from Scratch) or hit Devam on any previously saved subject card.
Track Your Focus Time:
The app switches to the timer screen, counting your active seconds in real-time.
You can Pause / Resume the session whenever needed.
Handle Early Breaks:
Click the Mola / Durdur (Break / Stop) button.
Select your reason from the popup menu to save the session instantly into your history log.
Review Past Performance:
Check your completed sessions, timestamps, and total accumulated hours under the Geçmiş (History) tab.
📱 Installation on iOS (iPhone / iPad)
Open your deployed GitHub Pages URL in Safari.
Tap the Share button in the bottom browser menu.
Select "Add to Home Screen".
Launch the app directly from your home screen for a full-screen, native application experience!
⚙️ Class Schedule Configuration
The app features a built-in schedule system that tracks your day dynamically. You can customize the schedule array inside the JavaScript code to match your exact institutional hours:
JavaScript
const classSchedule = [
    { start: "09:00", end: "10:00" },
    { start: "10:10", end: "11:10" },
