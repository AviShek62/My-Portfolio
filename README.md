# Avishek's Portfolio

A modern, responsive dark-mode portfolio website built with HTML, CSS, and JavaScript.

## Features

✨ **Modern Design**
- Clean, professional dark theme with gradient accents
- Responsive layout that works on all devices
- Smooth animations and transitions

📱 **Responsive**
- Mobile-friendly navigation with hamburger menu
- Optimized for desktop, tablet, and mobile devices

⚡ **Interactive**
- Smooth scrolling navigation
- Scroll-to-top button
- Intersection Observer for scroll animations
- Hover effects and transitions

🎨 **Customizable**
- Easy to update with your own content
- Gradient colors and spacing can be adjusted
- Font Awesome icons included

## File Structure

```
Portfolio/
├── index.html      # Main HTML file
├── styles.css      # Styling and responsive design
├── script.js       # JavaScript interactions
└── README.md       # This file
```

## Getting Started

1. Open `index.html` in your web browser
2. The site is self-contained and requires no build process

## Customization

### Update Your Information

Open `index.html` and update:

- **Name**: Change "Vivek" to your name
- **Title**: Update "Full Stack Developer & Problem Solver"
- **About Section**: Replace placeholder text with your bio
- **Skills**: Edit the skill tags in the About section
- **Projects**: Replace project cards with your own
- **Contact**: Update email and phone number
- **Social Links**: Update href values to your profiles

### Customize Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #667eea;      /* Main accent color */
    --secondary-color: #764ba2;    /* Secondary accent */
    --bg-dark: #0f172a;            /* Dark background */
    --bg-secondary: #1e293b;       /* Secondary background */
    --text-primary: #f1f5f9;       /* Main text color */
    --text-secondary: #cbd5e1;     /* Secondary text */
}
```

### Add More Projects

Copy a project card block in the `.projects-grid` section and update:
- Project image gradient
- Title and description
- Technology tags
- Links to GitHub and live demo

### Update Social Links

In the hero section, update the social media links:

```html
<a href="https://github.com/yourprofile" title="GitHub"><i class="fab fa-github"></i></a>
<a href="https://linkedin.com/in/yourprofile" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
```

## Responsive Breakpoints

- **Desktop**: Full layout
- **Tablet (≤768px)**: Single column for some sections
- **Mobile (≤480px)**: Optimized for small screens

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Icons

This portfolio uses [Font Awesome 6.4.0](https://fontawesome.com/) for icons. They load from a CDN, so make sure you have internet access or download Font Awesome locally.

## Tips

1. **Profile Picture**: Add a profile image by uploading it and using CSS to display it in the hero or about section
2. **SEO**: Update the `<title>` and add meta descriptions
3. **Performance**: Optimize images before adding them
4. **Analytics**: Add Google Analytics or similar tracking to `script.js`
5. **Form**: Implement a backend service (Formspree, Netlify Forms, etc.) for the contact form

## Deployment

### GitHub Pages (Free)
```bash
# Push your portfolio to a GitHub repo
# Go to Settings → Pages
# Select your branch and save
```

### Netlify (Free)
- Connect your GitHub repo or drag & drop files
- Auto-deploys on changes

### Vercel (Free)
- Import from GitHub
- Auto-deploys on push

### Traditional Hosting
Upload all files to your web hosting provider

## License

Feel free to use this template for your portfolio!

---

**Version**: 1.0  
**Last Updated**: 2026  
**Created with ❤️**
