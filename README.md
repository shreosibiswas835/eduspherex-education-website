# EduSphereX — Learning Platform UI

A refreshed, responsive multi-page education website with a clean visual system, light/dark theme, course discovery, filters, FAQ accordions, and accessible frontend form validation.

## Highlights
- Modern responsive design with mobile navigation and persistent light/dark mode
- Home, courses, categories, about, blog, contact, FAQ, login, registration, and policy pages
- Course search and category filtering
- Accessible form validation and demo feedback messages
- Existing project imagery and Gilroy font assets retained where applicable
- No framework or build step required

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a browser, or serve the folder with a local static server.

For example, with Python installed:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Important demo limitations
This is a frontend-only project. Login and registration do not authenticate users; contact/newsletter forms do not transmit or persist data; enrollment and payments are not implemented. Course details, prices, statistics, and policy copy are illustrative. Connect a secure backend and replace placeholder policies before production use.

## Structure
```text
EduSphereX/
├── index.html
├── assets/
│   ├── css/modern.css
│   ├── js/modern.js
│   ├── html/
│   ├── images/
│   └── font/
├── favicon.png
├── LICENSE
└── README.md
```

## Customization
Update theme variables at the top of `assets/css/modern.css`. Course data is currently authored in `assets/html/courses.html` and the homepage.
