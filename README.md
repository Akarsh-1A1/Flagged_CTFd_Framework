# Flagged – A CTF platform

A modular, API-first platform for managing Capture The Flag (CTF) competitions, built with **FastAPI** (Python) on the backend and **Next.js** (React) on the frontend.  
Developed as part of the IITISoC Cybersecurity project to provide a reliable, user-friendly, and extensible system for CTF event management.


## Table of Contents
- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation and setup](#installation-and-setup)
- [Screenshots](#screenshots)
- [Future Improvements](#future-improvements)
- [Contributors](#contributors)
- [License](#license)


## About <a name="about"></a>

Capture The Flag competitions are a fun and educational way to test cybersecurity skills.  
Our goal with this project was to create a CTF management platform that:
- Is lightwieght
- Follows API-first architecture
- Has a modern frontend UI
- Supports teams, challenges, scoring, and authentication
- Prioritizes extensibility for future features

The platform is suitable for university-level CTF events, cybersecurity clubs, or even small online competitions.


## Features <a name="features"></a>

- User & Team Management (Registration, login, management)
- Challenge Management (Static challenges, scoring logic)
- Role-Based Access Control
- API-first design for flexibility (can support mobile/CLI in the future)
- Email verification flows


## Tech Stack <a name="tech-stack"></a>

**Backend**
- FastAPI (with Pydantic models)
- SQLAlchemy ORM
- MariaDB/MySQL (Database)

**Frontend**
- Next.js (React)
- Tailwind CSS


## Installation and setup <a name="installation-and-setup"></a>

We use uv for python package management and pnpm for node package management. Ensure they are installed. Starting the backend and frontend servers is as simple as running the following commands in respective directories

`uv run fastapi dev`

and

`pnpm dev`

Configure the backend at `backend/app/config.py`.


## Screenshots <a name="screenshots"></a>

| Login Page | Dashboard | Scoreboard | AdminPanel |
|------------|-----------|------------|------------|
| ![Login](gallery/Login.png) | ![Dashboard](gallery/dashboard.png) | ![Scoreboard](gallery/scoreboard.png) | ![AdminPanel](gallery/AdminPanel.png) |


## Future Improvements <a name="future-improvements"></a>

- Support for instance-based challenges
- Plugin-based architecture for custom features
- Anti-cheating tools and personalized flags
- Mobile app / CLI support
- Detailed analytics for organizers
- Comprehensive documentation


## Contributors <a name="contributors"></a>

- ![Tanish Yadav](https://github.com/tanpsi) - 240041036
  
  Worked on FastAPI endpoints. Implemented backend authentication flow. Fixed multiple backend issues and implemented multiple DB operations.
- ![Akarsh Raj](https://github.com/Akarsh-1A1) - 240051003

  Frontend layout, theme, pages design, Created Login, Register, Home, Scoreboard, teams, Admin panel, Notifications pages. Set  Authentication flow, fixed and implemented some backend part ; Integration of Admin controls, Scoreboard, Challenges, Teams, Profile, Notifications, Email-Verification setup etc to backend.
- ![Subhanshu Kumar](https://github.com/Subhansh-1-u) - 240021019

  Pages design user, team, forget password, settings, flag submission logic (fast api rate limitter and redis implementation), some backend endpoints like reset password and send reset password email. Integration of settings, team, user, forget password etc to backend

- ![Vivek Sahu](https://github.com/viveksahu15) - 240005051

  Designed the challenge, profile, and settings pages, implemented them in code, and integrated the profile page with its respective backend endpoints, as well as integrated the challenge page with the backend.

- ![Sumit Modanwal](https://github.com/sumitmodanwal962) - 240004049

  Email verification
- ![Mohd Hassan Raza Ansari](https://github.com/hr5116) - 240008019

  Database models


## License <a name="license"></a>

This project is licensed under the MIT License - see the LICENSE file for details.
