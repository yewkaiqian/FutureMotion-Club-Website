# FutureMotion Club – Animation and Multimedia Website

## Overview

FutureMotion Club is an interactive, multi-page website designed for a university animation and multimedia club. It provides a centralised platform for students and creative media enthusiasts to explore animation projects, multimedia works, learning resources, tutorials and club events.

The website combines responsive web design, interactive JavaScript functionality, REST API integration and client-side data storage to deliver an engaging browsing experience.

## Live Demo

[Visit FutureMotion Club](https://justina-ops.github.io/FutureMotion-Club/)

## Key Features

- **Home Page** – Introduces the club, featured animations and creative resources.
- **About Page** – Presents the club's background, mission, committee members and core values.
- **Project Showcase** – Displays animation, video editing and multimedia projects with category filtering and video previews.
- **Interactive Gallery** – Supports image browsing, filtering, sorting, favourites and lightbox previews.
- **Tutorial Library** – Provides searchable and filterable learning resources, embedded video tutorials, learning categories and recently viewed tutorials.
- **Event Management** – Displays upcoming and past events, event countdowns, registration forms, event filtering and Google Calendar integration.
- **Multimedia Showcase** – Presents creative multimedia content through interactive visual components.
- **Contact Page** – Provides enquiry forms and weather information.
- **Theme Switching** – Supports dark and light modes with saved preferences.
- **Background Music** – Allows users to enable or disable background audio.
- **Social Media Integration** – Supports content sharing through social media platforms.

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and content |
| CSS3 | Responsive layouts, styling and animations |
| JavaScript | Dynamic content and interactive functionality |
| jQuery | AJAX requests and API integration |
| REST APIs | Retrieval of external data and resources |
| Local Storage | Persistent client-side data and preferences |
| Session Storage | Temporary session data and form drafts |
| Cookies | Consent management and user preferences |
| GitHub Pages | Website deployment and hosting |

## API Integration

| API | Purpose |
|---|---|
| GitHub REST API | Retrieve related repositories and learning resources for tutorials |
| Open Library API | Retrieve creative learning resources |
| Metropolitan Museum of Art Collection API | Retrieve artwork and visual references for the gallery |
| Open-Meteo API | Display weather information |

## Technical Implementation

- Responsive web design
- DOM manipulation
- Event-driven programming
- REST API integration
- AJAX and asynchronous data retrieval
- JSON data handling
- Client-side data persistence
- Dynamic searching, filtering and sorting
- Form validation
- Interactive modals and carousels
- CSS transitions and animations
- Multimedia embedding
- Social media sharing
- User preference management

## Repository Structure

| File or Directory | Description |
|---|---|
| `index.html` | Homepage |
| `about.html` | Club introduction and committee information |
| `projects.html` | Creative project showcase |
| `gallery.html` | Interactive visual gallery |
| `tutorials.html` | Tutorial library and learning resources |
| `events.html` | Club events and registration |
| `multimedia.html` | Multimedia showcase |
| `contact.html` | Contact and enquiry page |
| `css/` | Shared and page-specific stylesheets |
| `js/` | JavaScript modules and interactive functionality |
| `Images/` | Website images and visual assets |
| `music/` | Background audio |
| `video/` | Local video assets |

## Getting Started

1. Clone or download this repository.
2. Open the project folder using Visual Studio Code or another compatible editor.
3. Launch `index.html` using a local web server, such as the Live Server extension.
4. Navigate through the website to explore its features.

An internet connection is required for external API requests, embedded videos and externally hosted resources.

## Individual Contributions – Yew Kai Qian

### Tutorials Page

- Designed and developed the tutorial page layout, wireframes and mockups.
- Implemented dynamic tutorial searching, category filtering and sorting.
- Developed an interactive learning category carousel.
- Integrated embedded YouTube video tutorials.
- Implemented recently viewed tutorial tracking using Local Storage.
- Integrated the GitHub REST API using jQuery AJAX to retrieve related learning resources.
- Implemented tutorial sharing through social media platforms.

### Events Page

- Designed and developed the events page layout, wireframes and mockups.
- Implemented event searching, filtering and sorting.
- Developed dynamic event statuses and featured event countdowns.
- Implemented interactive event information and registration modals.
- Developed client-side event registration using Local Storage.
- Implemented temporary registration form drafts using Session Storage.
- Integrated Google Calendar event links.
- Implemented event sharing functionality and user feedback messages.

### Documentation and Research

- Conducted a comparative analysis of existing animation and multimedia websites.
- Evaluated existing website functionality, technical limitations and user experience.
- Documented the design and implementation of the Tutorials and Events pages.

## Contributors

| Contributor | Pages Developed |
|---|---|
| Leong Di Hao | Multimedia and Contact |
| Liew Jia Min | Projects and Gallery |
| Sek Siang Wee | Home and About |
| Yew Kai Qian | Tutorials and Events |

## Project Background

This project was developed collaboratively by four undergraduate students at Universiti Tunku Abdul Rahman (UTAR) as part of the Front-End Web Development coursework.

- **Course:** UCCD2323 – Front-End Web Development
- **Trimester:** June 2026
- **Project Type:** Academic Group Project
- **Group:** FutureMotion

## Project Limitations and Future Improvements

The current implementation is a client-side website without a dedicated backend or centralised database. Event registrations, browsing history and user preferences are stored locally within the user's browser.

Potential future improvements include:

- Backend and database integration
- User authentication and member profiles
- Centralised event registration
- Club administration dashboard
- Personalised tutorial recommendations
- Learning progress tracking
- Content management system (CMS)
