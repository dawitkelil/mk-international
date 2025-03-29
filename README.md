# ConsultPro Website

A modern, responsive website for a consulting company built with HTML5, CSS3, and JavaScript.

## Features

- Responsive design that works on all devices
- Modern and clean user interface
- Smooth scrolling navigation
- Contact form
- Animated sections and statistics
- Mobile-friendly navigation menu
- Social media integration

## Setup

1. Clone this repository:
```bash
git clone https://github.com/yourusername/consultpro-website.git
cd consultpro-website
```

2. Open the website locally:
- Simply open the `index.html` file in your web browser
- Or use a local server (recommended)

## Deployment to GitHub Pages

1. Create a new repository on GitHub

2. Push your code to GitHub:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/consultpro-website.git
git push -u origin main
```

3. Enable GitHub Pages:
- Go to your repository settings
- Scroll down to the "GitHub Pages" section
- Select the `main` branch as the source
- Click "Save"

Your website will be available at: `https://yourusername.github.io/consultpro-website`

## Customization

### Colors
To change the website's color scheme, modify the CSS variables in `styles/main.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --text-color: #1f2937;
    --light-text: #6b7280;
    --background: #ffffff;
    --section-bg: #f3f4f6;
}
```

### Content
- Update the text content in `index.html`
- Replace the placeholder images in the `assets` directory
- Update contact information and social media links

### Contact Form
To make the contact form functional, you'll need to:
1. Set up a backend server to handle form submissions
2. Update the form submission code in `scripts/main.js`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## License

This project is licensed under the MIT License - see the LICENSE file for details. 