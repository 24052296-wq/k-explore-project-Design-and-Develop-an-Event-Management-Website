# K Explore – Event Management Website

A responsive website where users can explore upcoming campus events, search and filter them, view details, and register for the ones they like.

**Live website:** https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
**GitHub repository:** https://github.com/YOUR-USERNAME/YOUR-REPO-NAME

## Features

- Hero section introducing the platform
- Event cards showing name, date, venue, category and a short description
- Search by event name or venue
- Filter events by category (Tech, Music, Workshop, Sports, Art)
- Event details popup with a live countdown timer
- Registration form with JavaScript validation (name, email, phone, event)
- Confirmation message after a successful registration
- Registrations saved in the browser using Local Storage
- Dark and light mode, remembered between visits
- Responsive layout for mobile, tablet and desktop

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, CSS variables, media queries)
- JavaScript (DOM manipulation, form validation, Local Storage, timers)
- Git and GitHub for version control
- GitHub Pages for deployment

## How It Works

- **Events data:** all events are stored in a JavaScript array. The cards are created from this array, so adding an event only means adding one object to the list.
- **Search and filter:** every time the user types or clicks a category, the array is filtered and the cards are drawn again.
- **Validation:** each field has a rule (for example, the phone number must be 10 digits). Errors appear below the field, and the form only submits when every rule passes.
- **Dark mode:** the colours are CSS variables. Switching modes changes their values, and the choice is saved in Local Storage.
- **Countdown:** a timer runs every second while the details popup is open and shows the time left until the event.

## Run Locally

1. Download or clone this repository.
2. Open `index.html` in any browser. No installation is needed.

## Project Structure

```
index.html   (HTML, CSS and JavaScript in one file)
README.md
```

## Future Improvements

- Backend and database to store registrations
- User login and an admin page to add events
- Email confirmation after registration
- Event images and a map of venues

## Author

YOUR NAME – K Explore Web Designing Task
