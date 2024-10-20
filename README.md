# Garbage Tracking System

## Overview

The Garbage Tracking System is a responsive web application designed to manage and monitor waste collection services. Built using HTML and CSS, this project demonstrates modern web design principles and responsive layouts without relying on JavaScript.

## Features

- Responsive design that works on desktop and mobile devices
- Multiple pages: Home, Services, About Us, and Contact
- Dashboard-style summary on the home page
- Service showcase with hover effects
- About Us page with team member profiles
- Contact form for user inquiries

## Project Structure

```
garbage-tracking-system/
│
├── index.html
├── services.html
├── about.html
├── contact.html
├── styles.css
├── images/
│   ├── truck.jpg
│   └── [other images]
├── videos/
│   ├── garbage_truck_video.mp4
│   └── services_video.mp4
└── README.md
```

## Setup

1. Clone the repository or download the project files.
2. Ensure all HTML files (index.html, services.html, about.html, contact.html) are in the root directory.
3. Make sure the styles.css file is in the root directory.
4. Create an `images` folder and add your image files, including `truck.jpg` for the hero image.
5. Create a `videos` folder and add your video files: `garbage_truck_video.mp4` and `services_video.mp4`.

## Customization

### Colors

The color scheme can be easily modified by changing the CSS variables in the `:root` selector in `styles.css`:

```css
:root {
    --primary-color: #4CAF50;
    --secondary-color: #45a049;
    --text-color: #333;
    --bg-color: #f4f4f4;
    --card-bg: #ffffff;
}
```

### Images

Replace the placeholder images with your own:

1. In the `images` folder, add your own images.
2. Update the `src` attributes in the HTML files to point to your new images.

### Content

Modify the content in each HTML file to match your specific garbage tracking system:

- Update text in headings, paragraphs, and list items.
- Adjust the dashboard summary numbers on the home page.
- Modify service descriptions on the services page.
- Update team member information on the about page.
- Change contact information on the contact page.

## Responsive Design

The layout is responsive and adapts to different screen sizes:

- Desktop: Full layout with grid-based designs
- Tablet: Adjusted grids and font sizes
- Mobile: Single column layout with stacked elements

## Browser Compatibility

This project is designed to work on modern browsers that support HTML5 and CSS3, including:

- Google Chrome (latest)
- Mozilla Firefox (latest)
- Safari (latest)
- Microsoft Edge (latest)

## Contributing

Contributions to improve the design or extend the functionality of this project are welcome. Please fork the repository and submit a pull request with your changes.

## License

This project is open-source and available under the MIT License.
