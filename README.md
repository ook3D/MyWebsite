# Modern Portfolio Website

A clean, modern, and fully responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- Modern and clean design
- Fully responsive (mobile, tablet, desktop)
- Smooth scrolling navigation
- Interactive animations
- Mobile-friendly hamburger menu
- Optimized for performance
- Ready to deploy on Cloudflare Pages

## Project Structure

```
MyWebsite/
├── index.html      # Main HTML file
├── styles.css      # Styling and responsive design
├── script.js       # Interactive functionality
└── README.md       # This file
```

## Customization

### Update Your Information

1. **Personal Details** - Edit `index.html`:
   - Replace "Your Name" with your actual name
   - Update the hero subtitle with your role
   - Modify the about section with your bio

2. **Projects** - Edit the project cards in `index.html`:
   - Update project titles and descriptions
   - Add your project links
   - Replace technology tags
   - Add project images (replace placeholder-image divs)

3. **Skills** - Modify the skills section in `index.html`:
   - Add or remove skills
   - Organize by categories that fit your expertise

4. **Contact Links** - Update contact information in `index.html`:
   - Add your email address
   - Update social media links (GitHub, LinkedIn, Twitter)

5. **Colors** - Customize in `styles.css`:
   - Edit CSS variables in `:root` section
   - Change gradient colors in `.hero` section

## Deploy to Cloudflare Pages

### Option 1: Deploy via Git Integration (Recommended)

1. Push your code to a GitHub repository
2. Log in to [Cloudflare Dashboard](https://dash.cloudflare.com/)
3. Go to "Workers & Pages" > "Create application" > "Pages"
4. Click "Connect to Git"
5. Select your repository
6. Configure build settings:
   - **Build command**: Leave empty (static site)
   - **Build output directory**: `/`
7. Click "Save and Deploy"

Your site will be live at `https://your-project.pages.dev`

### Option 2: Direct Upload

1. Log in to [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. Go to "Workers & Pages" > "Create application" > "Pages"
3. Click "Upload assets"
4. Drag and drop all your files (index.html, styles.css, script.js)
5. Click "Deploy site"

### Custom Domain

To use a custom domain:
1. In your Pages project, go to "Custom domains"
2. Click "Set up a custom domain"
3. Follow the instructions to configure your DNS

## Local Development

Simply open `index.html` in your web browser to view the site locally.

For a better development experience with live reload:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Performance

This site is optimized for performance:
- Minimal dependencies (no frameworks)
- Lightweight CSS and JavaScript
- Fast loading times
- Mobile-optimized

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

Feel free to use this template for your personal portfolio.
