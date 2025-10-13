Calendar App — Test Task (React + TypeScript)

This project is a calendar management application built with React and TypeScript. It allows users to create, edit, delete, and manage events on a visual calendar interface with color selection, drag-and-drop, and multiple views (Month, Week, Day).

Features and Requirements:
• Full copy of the provided layout (calendar view with sidebar and header).
• Ability to add a new event (max 30 chars) for a user-entered date and time.
• Display events in correct time order.
• Allow the user to select a color when creating or editing an event.
• Properly display overlapping events that occur at the same time.
• Ability to edit events – text, day, time, and color.
• Ability to delete events.
• Ability to drag and drop events.
• Ability to change months, weeks, or days by click.
• Save all events to localStorage for persistence.
• Deploy the project on GitHub Pages.

Tech Stack: React 18, TypeScript, Tailwind CSS (or MUI), react-big-calendar, Context API for state, and Vite (or CRA) as build tool. Hosting is done via GitHub Pages.

How it works:
All events are stored in localStorage under the key “calendarEvents”. When a user adds, edits, or deletes an event, the state is updated and synced with storage. The interface updates instantly without page reloads. The calendar supports drag-and-drop and custom event colors.

Installation:

Clone the repository:
git clone https://github.com/SergeyGetman/Aida-Tested

Install dependencies:
npm install

Run in development mode:
npm run dev

Build for production:
npm run build

Deploy to GitHub Pages:
npm run deploy

Layout description:
The layout is a full replica of the provided example — a left sidebar with navigation (Home, Dashboard, Inbox, Products, etc.), a top header with search and profile, and a main calendar section displaying user events.

Author:
Serhii Kushneorv — Frontend Developer (React / TypeScript / JavaScript)


