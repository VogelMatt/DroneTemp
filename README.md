# Drone Photography Landing Page

A modern, responsive landing page for drone photography and videography services. This single-page website features a stunning hero section, services overview, and a contact form.

## Features

- 📱 Fully responsive design
- ✨ GSAP animations
- 🎨 Modern UI with hover effects
- 📝 Contact form
- 🖼️ Service showcase section

## Getting Started

### Prerequisites

- A web server or hosting service to deploy the HTML file
- Basic understanding of HTML/CSS/JavaScript

### Installation

1. Download all files to your local machine or server
2. Replace the placeholder images:
   - Hero section background (`/api/placeholder/1920/1080`)
   - Service icons (`/api/placeholder/64/64`)

### File Structure

```
drone-landing-page/
│
├── index.html       # Main HTML file containing all code
└── README.md        # This file
```

## Customization

### Changing Colors

The main colors used in the site are:
- Primary Blue: `#00a8ff`
- Hover Blue: `#0097e6`
- Background Gray: `#f5f6fa`

To modify these colors, update the following CSS properties:
- `.cta-button` - background-color
- `.contact` - background-color
- `button` - background-color

### Modifying Content

#### Hero Section
Locate the `<section class="hero">` element to modify:
- Main heading
- Subheading
- Call-to-action button text

#### Services Section
Find the `<section class="services">` element to:
- Add/remove service cards
- Modify service descriptions
- Update service icons

#### Contact Form
The contact form is in the `<section id="contact">` element:
- Add additional form fields
- Modify labels
- Change button text

### Animation Settings

Animations are controlled by GSAP in the `<script>` section at the bottom of the file. Modify the following properties:
- `duration` - animation length
- `delay` - time before animation starts
- `ease` - animation timing function

## Dependencies

- [GSAP](https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js) - For animations

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Form Integration

The contact form requires backend integration to function. To make it work:

1. Add an `action` attribute to the form element with your backend endpoint
2. Add `name` attributes to the form inputs
3. Implement server-side form processing
4. Add form validation and success/error handling

Example backend integration:

```html
<form class="contact-form" action="/submit-form" method="POST">
```

## Performance Optimization

For better performance:

1. Optimize images before replacing placeholders
2. Consider lazy loading for images
3. Minify CSS and JavaScript
4. Use a CDN for faster asset delivery

## Contributing

Feel free to submit issues and enhancement requests!


## Support

For support, please contact [your-email@example.com]

## Acknowledgments

- GSAP for animation library
- Google Fonts for typography
