# TaskFlow Pro

TaskFlow Pro is a modern, responsive personal task management web application built with HTML, CSS, and Vanilla JavaScript. It features a sleek, dark-themed UI and provides an intuitive dashboard to track productivity, manage tasks, and maintain streaks.

## Features

- **User Authentication:** Simple login and registration system.
- **Task Management:** Add, toggle completion, and delete tasks.
- **Categorization & Priorities:** Assign categories (Work, Personal, Learning, Health, Other) and priorities (High, Medium, Low) to tasks.
- **Due Dates:** Set due dates and easily spot overdue tasks.
- **Dashboard & Insights:** View overall progress, current streak, category breakdowns, and daily productivity insights.
- **Filtering & Searching:** Filter tasks by status (All, Active, Completed, Overdue) and search by keywords.
- **Local Storage:** All user and task data is persisted locally in your browser using `localStorage`.

## Technologies Used

- **HTML5**
- **CSS3** (Flexbox, CSS Grid, Glassmorphism effects)
- **Vanilla JavaScript** (ES6+)
- **FontAwesome** (Icons)
- **Google Fonts** (Inter)

## How to Run

1. Clone or download this repository.
2. Open `index.html` in your preferred modern web browser.
3. No build tools or server required!

## Project Structure

- `index.html`: Contains all the markup, styles, and application logic in a single file for easy deployment and usage.

## Data Storage

The application uses the browser's `localStorage` to save:
- Registered users (`taskflow_users`)
- Current logged-in user (`taskflow_current_user`)
- User-specific tasks (`taskflow_tasks_[user_id]`)
- User streaks and activity tracking (`taskflow_streak_[user_id]`, `taskflow_last_active_[user_id]`)
