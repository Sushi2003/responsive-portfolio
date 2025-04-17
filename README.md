# Responsive Portfolio Website

A modern, responsive portfolio website template built with HTML, CSS, and JavaScript.

## Features

- Fully responsive design that works on all devices
- Modern and clean UI with smooth animations
- Mobile-friendly navigation menu
- Sections for showcasing projects, skills, and contact information
- Contact form with basic validation
- Smooth scrolling navigation

## Technologies Used

- HTML5
- CSS3 (Flexbox & CSS Grid)
- JavaScript (Vanilla JS)
- Font Awesome icons

## How to Use

1. Clone this repository
2. Customize the content in `index.html` with your own information
3. Modify the styles in `styles.css` to match your personal branding
4. Add your own projects and information
5. Deploy to your preferred hosting platform

## Customization

### Changing Colors

The main colors are defined as CSS variables in the `:root` selector in `styles.css`. Update these values to change the color scheme:

```css
:root {
    --primary-color: #4a6bff;
    --secondary-color: #6c757d;
    --dark-color: #343a40;
    --light-color: #f8f9fa;
    --success-color: #28a745;
    --danger-color: #dc3545;
    --transition-speed: 0.3s;
}
```

### Adding Projects

To add a new project, copy the following HTML structure and add it to the projects grid in `index.html`:

```html
<div class="project-card">
    <div class="project-img">
        <div class="project-placeholder"></div>
        <!-- Or add an actual image: -->
        <!-- <img src="path/to/project-image.jpg" alt="Project Name"> -->
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Project description goes here.</p>
        <div class="project-tags">
            <span>HTML</span>
            <span>CSS</span>
            <span>JavaScript</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link"><i class="fas fa-globe"></i> Live</a>
            <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
        </div>
    </div>
</div>
```

## License

This project is open source and available under the [MIT License](LICENSE).