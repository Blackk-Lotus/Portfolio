# Aakash Gujja - Portfolio Website

A modern, responsive portfolio website showcasing cybersecurity research, information security management experience, and projects.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Particle effects, smooth scrolling, and hover animations
- **Sections Include**:
  - Hero/Landing page with social links
  - About section with statistics
  - Experience timeline
  - Featured projects showcase
  - Skills and expertise
  - Contact form

## Technologies Used

- HTML5
- CSS3 (Custom animations, Grid, Flexbox)
- Vanilla JavaScript
- Font Awesome Icons

## Setup

1. Clone this repository:
```bash
git clone https://github.com/Blackk-Lotus/portfolio.git
cd portfolio
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

3. Visit `http://localhost:8000` in your browser

## Deployment to GitHub Pages

1. Push your code to GitHub:
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

2. Go to your repository settings on GitHub
3. Navigate to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Your site will be live at `https://blackk-lotus.github.io/portfolio/`

## Customization

### Update Personal Information

1. **Contact Email**: Replace `your.email@example.com` in `index.html`
2. **Experience**: Edit the timeline section with your actual work history
3. **Projects**: Update project cards with your real projects
4. **Skills**: Modify skill tags to match your expertise
5. **Statistics**: Update the numbers in the about section

### Change Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #00ff88;
    --secondary-color: #0a192f;
    --accent-color: #64ffda;
    /* Customize other colors */
}
```

### Add Your Projects

Update the projects section in `index.html` with your actual GitHub repositories and projects.

## Contact Form

The contact form currently shows an alert message. To make it functional:

1. Integrate with a backend service (e.g., Formspree, EmailJS)
2. Or use a serverless function (Netlify Functions, Vercel)
3. Update the form handler in `script.js`

## License

MIT License - feel free to use this template for your own portfolio!

## Credits

Built by Aakash Gujja
- GitHub: [@Blackk-Lotus](https://github.com/Blackk-Lotus)
- LinkedIn: [aakash-g-a27039182](https://linkedin.com/in/aakash-g-a27039182)

---

**Note**: Remember to update all placeholder content with your actual information before deploying!
