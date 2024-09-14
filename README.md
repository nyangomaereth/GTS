# Garbage Trucking System

## Project Overview

The Garbage Trucking System is a web-based application designed to optimize waste collection routes, manage truck fleets, and improve overall efficiency in garbage collection operations. This project is built using HTML, CSS, and JavaScript, implementing a single-page application (SPA) architecture.

## Table of Contents

1. [File Structure](#file-structure)
2. [Setup and Installation](#setup-and-installation)
3. [Code Explanation](#code-explanation)
   - [HTML (index.html)](#html-indexhtml)
   - [CSS (styles.css)](#css-stylescss)
   - [JavaScript (app.js)](#javascript-appjs)
4. [Features](#features)
5. [Future Enhancements](#future-enhancements)

## File Structure

```
garbage-trucking-system/
│
├── index.html
├── styles.css
├── app.js
└── README.md
```

## Setup and Installation

1. Clone the repository or download the files.
2. Open the `index.html` file in a web browser.

Note: This is a front-end only implementation. For full functionality, you would need to integrate with a back-end server and database.

## Code Explanation

### HTML (index.html)

The `index.html` file serves as the main structure of the application.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags, title, and links to CSS and Font Awesome -->
</head>
<body>
    <header>
        <!-- Navigation menu -->
    </header>

    <main id="app">
        <!-- Dynamic content will be loaded here -->
    </main>

    <footer>
        <!-- Footer content -->
    </footer>

    <script src="app.js"></script>
</body>
</html>
```

Key points:
- The `<main id="app">` element is where the dynamic content will be rendered.
- The navigation menu in the `<header>` allows users to switch between different views.
- The `app.js` script is linked at the end of the body to ensure DOM content is loaded before the script runs.

### CSS (styles.css)

The `styles.css` file contains all the styles for the application.

Key sections:
1. Basic Reset and General Styles
2. Header and Footer Styles
3. Dashboard Styles
4. Banner Styles
5. Form Styles
6. Table Styles

Notable features:
- Responsive grid layout for the dashboard using CSS Grid.
- A banner section with a background image and overlaid text.
- Consistent color scheme and typography throughout the application.

### JavaScript (app.js)

The `app.js` file contains the main application logic, implementing a simple routing system and rendering functions for different views.

Key components:

1. `app` object: The main application object that encapsulates all functionality.

2. Initialization:
   ```javascript
   init() {
       this.cacheDom();
       this.bindEvents();
       this.render('dashboard');
   }
   ```
   - Caches DOM elements
   - Binds event listeners
   - Renders the initial dashboard view

3. Event Handling:
   ```javascript
   handleNavClick(e) {
       // ... handles navigation clicks and triggers appropriate render
   }
   ```

4. Rendering:
   ```javascript
   render(page) {
       // ... switches between different page renders based on navigation
   }
   ```

5. Page-specific render functions:
   - `renderDashboard()`
   - `renderRoutes()`
   - `renderTrucks()`
   - `renderSchedule()`
   - `renderReports()`

Each render function returns an HTML string that is inserted into the main `<div id="app">` element.

## Features

1. Dashboard with key metrics
2. Route management view
3. Truck fleet management view
4. Schedule management view
5. Reporting view
6. Responsive design for various screen sizes

## Future Enhancements

1. User authentication and authorization
2. Integration with a back-end server for data persistence
3. Real-time tracking of trucks using mapping services
4. Advanced analytics and reporting features
5. Mobile app for drivers

---

This project serves as a foundation for a Garbage Trucking System and can be extended with more features and back-end integration as needed.