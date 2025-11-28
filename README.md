📁 Assignment 3 – Advanced Functionality
Personal Portfolio Web Application

This repository contains my implementation for Assignment 3 – Advanced Functionality, where I continued developing my personal portfolio web application.
The focus for this stage of the project was to implement API integrations, complex logic, state management, performance improvements, and a documented use of AI tools.

🚀 Overview

This version of my portfolio expands on the structure built in Assignments 1 and 2 and introduces more advanced features including:

Live API-powered components (GitHub, weather, quotes)

Complex client-side logic (filtering, sorting, form validation)

State persistence using localStorage

Optimized performance and accessibility

Detailed documentation of AI-assisted development

The entire application runs on HTML, CSS, and vanilla JavaScript with zero build tools, making it lightweight, fast, and easy to run locally.

📂 Project Structure
assignment-3/
├── README.md
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── assets/
│   └── images/
├── docs/
│   ├── ai-usage-report.md
│   └── technical-documentation.md
└── .gitignore

🧠 Key Features
🔗 1. External API Integrations

Implemented fully-functional fetch requests with graceful error handling:

GitHub API

Displays my latest repositories

Shows language, stars, forks, last updated time

Includes skeleton loaders and offline fallback messaging

Weather API (wttr.in)

Fetches live weather data (temperature, humidity, conditions)

Converts weather codes to emoji for friendly UI

Quotes API (Quotable → ZenQuotes → Local fallback)

Motivational tech/programming quotes

Multiple fallback layers ensure this widget never fails

All API responses are sanitized for safety before rendering.

🧩 2. Complex Logic

Built several multi-step interactions:

Project Explorer

Search with debounce

Tag-based filtering

Difficulty filter

Sorting (alphabetical/date)

Empty-state handling

Persistent preferences

Contact Form

Email + message validation

Live character counter

Prevents invalid submissions

Success toast notifications

Skills and Sections

Animated skill bars

Category filtering

Collapsible website sections with saved state

💾 3. State Management

Using localStorage, the site remembers:

Theme (light/dark/system)

Visitor name (personalized greeting)

Section visibility

Project filter options

Skills category selection

Everything restores instantly on page reload.

⚡ 4. Performance Enhancements

Lazy-loaded images

Single optimized CSS + JS payload

Debounced input handlers

No external frameworks → fast loading

Prefers-reduced-motion support

Lighthouse-driven cleanup of unused code and assets

♿ 5. Accessibility & UX

Proper semantic HTML

ARIA labels / aria-expanded state syncing

Keyboard navigation + skip link

Toast messages in aria-live regions

Sticky nav, back-to-top button, scroll indicator

Mobile-responsive layout

🛠 How to Run the Project Locally

Clone the repository:

git clone https://github.com/<your-username>/assignment-3.git


Open the project folder:

cd assignment-3


Open index.html in any modern web browser.

No installation or build steps required—it's a pure static site.

🧪 Testing Summary

The site has been manually tested for:

API success + failure states

All filter/sort combinations

Form validation and toasts

Section toggle memory

Theme switching

Mobile vs desktop breakpoints

Keyboard navigation

Browser compatibility (Chrome, Edge, Firefox, Safari)

🤖 AI Usage Summary

A detailed log is available in docs/ai-usage-report.md, but here is a high-level summary:

AI Tools Used

Lovable (UI design exploration)

ChatGPT (planning, research)

GitHub Copilot (boilerplate suggestions)

Cursor (debugging, refactoring, documentation review)

My Workflow

AI helped with brainstorming, structure, documentation, and small code suggestions.

I manually reviewed, edited, tested, and adapted every piece of code.

No unedited AI-generated code was copied directly.

All usage is fully documented per assignment requirements.

📄 Additional Documentation
File	Description
docs/technical-documentation.md	Full breakdown of architecture, APIs, logic, and performance work
docs/ai-usage-report.md	Required AI usage log with prompts, responses, edits, and reflections
🌐 Optional: Deployment

You can deploy this project using:

GitHub Pages

Netlify

Vercel

If deployed, include your link here:

🔗 Live Demo: (Add link if available)

📜 Academic Integrity Statement

All work in this project is my own.
AI tools assisted in planning, debugging, and documentation, but all final code and decisions were written, edited, or validated by me.
AI usage is fully documented as required.

✅ Final Notes

This portfolio now includes advanced interactivity, external data, and persistent state, fulfilling all Assignment 3 requirements. It also sets a strong foundation for the final project and future upgrades.

If you need help generating badges, screenshots, or a prettier README layout, feel free to ask!