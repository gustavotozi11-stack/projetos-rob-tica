# Children's Robotics Projects Landing Page

## Overview
A static marketing/landing page for "Children's Robotics Projects" (Portuguese language). Built with React + Tailwind CSS, compiled into static assets using Vite. Includes Facebook Meta Pixel tracking.

## Project Structure
```
.
├── index.html              # Main HTML entry point
├── js/
│   ├── index-Bzq_0qp-.js  # Main React application bundle
│   └── fbevents.js         # Facebook Pixel library
├── css/
│   └── index-DFr47thn.css # Compiled Tailwind CSS
└── vite.svg                # Favicon
```

## Running the Project
- **Workflow**: "Start application" runs `python3 -m http.server 5000 --bind 0.0.0.0`
- **Port**: 5000 (webview)
- **Type**: Static file server (no build step needed)

## Deployment
- **Target**: Static site
- **Public Directory**: `.` (root)
- Files are pre-built production assets; no build step required for deployment.

## Technologies
- React (pre-compiled)
- Tailwind CSS (pre-compiled)
- Lucide React icons
- Facebook Meta Pixel (ID: 700974852449522)
- Python HTTP server for local development
