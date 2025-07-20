# The Grateful Life Family Foundation Website

A modern, responsive website for The Grateful Life Family Foundation (TGLFF), a registered Tennessee charity dedicated to elevating collective consciousness and fostering community wisdom at Lake Waldensia in Ozone, TN.

## About TGLFF

The Grateful Life Family Foundation operates under the mission "Changing the world, one mind at a time" and "Helping humans be better people." Located on a 372-acre wooded property at Lake Waldensia, TGLFF offers various programs and initiatives including:

- Guest Programs with accommodation options
- Volunteer Programs for consciousness development
- Resident Partner Programs for deeper involvement
- 1% Partner Programs for long-term community building
- Trail of Trees initiative honoring the Trail of Tears

## Website Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with natural color palette
- **Accessibility**: WCAG compliant with proper semantic HTML and keyboard navigation
- **SEO Optimized**: Meta tags, structured data, and optimized content
- **Interactive Elements**: Smooth scrolling, hover effects, and form handling
- **Performance Optimized**: Compressed images and efficient CSS/JS

## Technology Stack

- **HTML5**: Semantic markup with proper structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom properties
- **Vanilla JavaScript**: Interactive functionality without dependencies
- **Google Fonts**: Inter and Playfair Display for typography
- **Responsive Images**: Optimized for various screen sizes

## Deployment to GitHub Pages

### Option 1: Direct Upload
1. Create a new repository on GitHub
2. Upload all files from this directory to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch" and choose "main" branch
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Git Deployment
```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: TGLFF website"

# Add remote origin (replace with your repository URL)
git remote add origin https://github.com/yourusername/tglff-website.git

# Push to GitHub
git push -u origin main
```

### GitHub Pages Configuration
1. In your repository, go to Settings > Pages
2. Source: Deploy from a branch
3. Branch: main / (root)
4. Click Save

Your website will be live at: `https://yourusername.github.io/tglff-website`

## File Structure

```
tglff-website/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css       # Main stylesheet
│   ├── js/
│   │   └── script.js       # JavaScript functionality
│   └── images/             # Website images
│       ├── lake-waldensia-hero.jpg
│       ├── community-tree-planting.jpg
│       └── [other images]
└── README.md               # This file
```

## Customization

### Colors
The website uses CSS custom properties for easy color customization. Edit the `:root` section in `assets/css/style.css`:

```css
:root {
    --primary-green: #2d5016;
    --secondary-green: #4a7c59;
    --golden-accent: #daa520;
    /* ... other colors */
}
```

### Content
All content can be edited directly in `index.html`. The website is structured with semantic sections:
- Hero section
- About section
- Programs section
- Trail of Trees section
- Community section
- Donation section
- Contact section

### Images
Replace images in the `assets/images/` directory. Ensure new images are optimized for web use (compressed and appropriately sized).

## Contact Information

For questions about TGLFF or this website:

- **Email**: TGLFF.org@gmail.com
- **Phone**: (423) 307-6008
- **Address**: PO Box 352, Ozone, TN 37854
- **Location**: 1824 Millstone Mountain Rd, Rockwood, TN 37854

## License

This website is created for The Grateful Life Family Foundation. All content and images are property of TGLFF unless otherwise specified.

---

*Website created with modern web standards and optimized for GitHub Pages deployment.*

