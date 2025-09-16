# Vinícius Galvão - Portfolio

A simple, clean portfolio website using the mnmlsm Linkfree template. This site serves as a central hub linking to my data science projects, blog, and professional profiles.

## 🚀 Live Site

Visit the live site at: [https://viniciusgalvaoia.github.io](https://viniciusgalvaoia.github.io)

## 📁 Project Structure

```
viniciusgalvaoia.github.io/
├── index.html           # Main portfolio page
├── style.css           # Styling and theme
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5**: Clean, semantic markup
- **CSS3**: Modern styling with CSS variables
- **GitHub Pages**: Hosting platform
- **mnmlsm Linkfree**: Minimalist template

## 🚀 Getting Started

### Testing Locally

Since this is a simple static site, you can test it locally in several ways:

#### Option 1: Simple File Opening
1. Open `index.html` directly in your browser
2. The site will work, but some features might be limited

#### Option 2: Local Server (Recommended)
1. Navigate to your project directory:
```bash
cd /Users/strider/Documents/private/viniciusgalvaoia.github.io
```

2. Start a simple HTTP server:
```bash
# Using Python 3
python3 -m http.server 8000

# Or using Python 2
python -m SimpleHTTPServer 8000

# Or using Node.js (if you have it installed)
npx serve .
```

3. Open your browser and visit `http://localhost:8000`

#### Option 3: Using Live Server (VS Code)
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 📝 Customization

### Updating Links

Edit the links in `index.html`:

```html
<div id="links">
    <a class="link" href="https://github.com/viniciusgalvaoia" rel="noopener">💻 GitHub - Open Source Projects</a>
    <a class="link" href="https://linkedin.com/in/viniciusgalvaoia" rel="noopener">💼 LinkedIn - Professional Profile</a>
    <a class="link" href="https://your-blog-url.com" rel="noopener">📝 Blog - Data Science Articles</a>
    <a class="link" href="https://your-data-apps-url.com" rel="noopener">📊 Data Apps - Interactive Dashboards</a>
    <a class="link" href="mailto:viniciusgalvaoia@gmail.com" rel="noopener">✉️ Email - Get In Touch</a>
</div>
```

### Updating Profile Photo

Change the profile photo URL in `index.html`:

```html
<img id="userPhoto" src="https://avatars.githubusercontent.com/u/53791129" alt="Vinícius Galvão">
```

### Customizing Colors

Edit the CSS variables in `style.css`:

```css
:root {
    --font: 'Roboto Mono', monospace;
    --background: white;
    --color: #232333;
}
```

## 🎨 Features

- **Minimalist Design**: Clean, distraction-free interface
- **Responsive**: Works on all devices
- **Dark Mode Support**: Automatically adapts to system preferences
- **Fast Loading**: Optimized for performance
- **Accessible**: Semantic HTML and proper contrast
- **Hover Effects**: Subtle animations for better UX

## 🚀 Deployment

### Deploy to GitHub Pages

1. Commit your changes:
```bash
git add .
git commit -m "Update portfolio links and styling"
```

2. Push to GitHub:
```bash
git push origin main
```

3. GitHub Pages will automatically deploy your site

### Custom Domain (Optional)

1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings to use your custom domain

## 📞 Contact

- **Email**: viniciusgalvaoia@gmail.com
- **GitHub**: [@viniciusgalvaoia](https://github.com/viniciusgalvaoia)
- **LinkedIn**: [viniciusgalvaoia](https://linkedin.com/in/viniciusgalvaoia)

---

Made with ❤️ by Vinícius Galvão using the mnmlsm Linkfree template
