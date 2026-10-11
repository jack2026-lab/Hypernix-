# Hypernix-# Hostel Attendance Tracker

## About
A web-based portal designed for hostel wardens and administrators to efficiently maintain, track, and record daily student attendance. 

## Tech Stack
* **Frontend:** HTML, CSS, and JavaScript (located in the `/public` directory).
* **Backend:** Node.js using Netlify Serverless Functions (`/netlify/functions`).
* **Deployment/Hosting:** Netlify (configured via `netlify.toml`).

## Core Features Needed
* **Student Roster:** A clean UI table displaying all currently registered hostel students.
* **Daily Attendance Interface:** Buttons or toggles to mark students as "Present", "Absent", or "On Leave" for the current date.
* **Record Viewing:** A simple date-picker to view historical attendance logs.
* **API Integration:** The frontend needs to communicate securely with the serverless backend to save the data.

## Jules Implementation Task
Jules, please scaffold the initial frontend UI in `public/index.html` with a basic layout to display a list of students and mark their attendance. Next, set up the corresponding REST API endpoints in `netlify/functions/api.mjs` to handle GET (fetch the roster) and POST (submit attendance) requests. For this initial setup, please mock the database using a temporary in-memory array or a local JSON file so the app is functional for testing.
