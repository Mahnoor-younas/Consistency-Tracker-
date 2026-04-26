# 🗓️ Consistency Tracker

A simple and motivating habit tracking application that helps users build daily consistency by logging habits, tracking streaks, and staying accountable every day.

---

## 🛠️ Technologies

- `HTML5`
- `CSS3`
- `JavaScript (ES6+)`
- `LocalStorage API`
- `Git & GitHub`

---

## ✨ Features

Here's what you can do with Consistency Tracker:

- **Add Habits:** Create and manage your own custom daily habits to track.

- **Daily Check-in:** Mark habits as complete each day with a single click.

- **Streak Counter:** Keep track of how many days in a row you've stayed consistent.

- **Progress Visualization:** See your daily and weekly progress at a glance.

- **Persistent Data:** Your habits and streaks are saved using `LocalStorage` — no data is lost on refresh.

- **Responsive Design:** Works smoothly on both desktop and mobile screens.

---

## ⚙️ The Process

I started by planning the structure of the app — what data needs to be stored and how habits would be tracked daily. Then I built the basic HTML layout with sections for adding habits and viewing progress.

Next, I used JavaScript to handle the core logic — adding new habits, marking them as complete, and calculating streaks based on consecutive days. I made sure the streak resets if a day is missed, keeping the tracker honest and motivating.

To make the data persist between sessions, I used the `LocalStorage` API so all habits and progress are saved in the browser. This way, users don't lose their data when they close or refresh the page.

Finally, I styled the app with CSS to make it clean, minimal, and easy to use. I focused on making the UI feel rewarding so users feel motivated to come back every day.

---

## 🧠 What I Learned

During this project, I picked up important skills around data management and building habit-forming user experiences.

### 💾 LocalStorage:

- **Data Persistence:** I learned how to save and retrieve data using `localStorage.setItem()` and `localStorage.getItem()`.
- **JSON Handling:** I practiced converting objects to JSON strings and parsing them back using `JSON.stringify()` and `JSON.parse()`.

### 🧮 Logic Building:

- **Streak Calculation:** I learned how to compare dates and calculate consecutive day streaks using JavaScript `Date` objects.
- **Conditional Rendering:** I practiced showing different UI states based on whether a habit is completed or not.

### 🎨 UI & Styling:

- **Minimalist Design:** I focused on keeping the UI clean and distraction-free so users stay focused on their habits.
- **Dynamic DOM Updates:** I got better at updating the page in real time without reloading using JavaScript.

### 📦 Overall Growth:

This project taught me that building something useful doesn't have to be complex. It was about solving a real problem — staying consistent — and turning that into a simple, functional app. It improved my logical thinking and gave me confidence to build more projects.

---

## 💡 How Can It Be Improved?

- Add a calendar view to visualize completed days.
- Add categories for habits (health, study, fitness, etc.).
- Add motivational quotes or rewards for long streaks.
- Allow users to set daily reminders or notifications.
- Add a dark mode and light mode toggle.
- Show weekly and monthly progress charts.
- Allow users to delete or edit existing habits.

---

## 🚀 Running the Project

To run the project in your local environment, follow these steps:

1. Clone the repository to your local machine.
2. Open the project folder.
3. Open `index.html` in your browser — no build step or server needed!

---

## 🎥 Video

https://github.com/user-attachments/assets/4f0d4c9c-f5f2-45ba-838a-489dba5aaf53
