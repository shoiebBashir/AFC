# AFC Website

A single-page website for Amjad Fayez Eid Al Adama General Contracting Est., based in Wadi Al Dawasir, Saudi Arabia. It presents the company's services, work process, projects, service areas, and contact information.

## Features

- Responsive layout for desktop and mobile
- Language selector for English, Arabic, Chinese, Urdu, and Hindi
- Service, project, gallery, FAQ, careers, and contact sections
- Project photos stored locally in `assets/`

## Run locally

No build tools or package installation are required. From the project directory, start a basic local web server:

```powershell
py -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000). You can also open `index.html` directly in a browser.

## Project files

- `index.html` contains the page structure, styles, and client-side scripts.
- `assets/afcimg1.jpg` through `assets/afcimg4.jpg` are the site's local image assets.

To replace a project photo, update its image path in `index.html` and put the new image in `assets/`.