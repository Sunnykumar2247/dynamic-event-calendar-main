## Installation and Usage

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Steps to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/sunnykumar2247/dynamic-event-calendar.git
   ```
2. Navigate to the project directory:
   ```bash
   cd dynamic-event-calendar
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
5. Open your browser and navigate to `http://localhost:3000` to view the app.

## Deployed Application
Access the live version of the app here: [Deployed Link](https://dynamic-event-calendar-beta.vercel.app/) 
🌟 Features
📅 Calendar View
Displays a calendar grid for the current month with all days properly aligned.

Seamlessly navigate between months using "Previous" ⬅️ and "Next" ➡️ buttons.

Highlights the current day 🔵 and the selected day 🔘 for better visual clarity.

📝 Event Management
Easily add events by clicking on any day in the calendar.

Edit ✏️ or delete 🗑️ events using an intuitive interface.

Event details include:

📌 Event name

🕒 Start & End time

🧾 Optional description

📋 Event List & 🔍 Filtering
View all events for the selected day in a modal or side panel.

Filter events 🔎 by keywords for efficient schedule navigation.

🧲 Drag-and-Drop Scheduling
Reschedule events effortlessly by dragging and dropping them to different days on the calendar.

💾 Data Persistence
Events are stored using localStorage 🗂️, ensuring your data stays even after refreshing the page.

📤 Export Functionality
Export your events for any month in JSON 📄 or CSV 📊 format for easy backup or sharing.

🎨 Visual Enhancements
Color-coded events by category (🧑‍💼 Work, 🏡 Personal, ✨ Others) for easy identification.

Distinct styles for weekends (🛌) and weekdays (📆) to enhance readability.

🧠 Intelligent Scheduling
Handles complex date transitions (like month-end to next month).

Prevents scheduling conflicts 🚫 by detecting overlapping events.
