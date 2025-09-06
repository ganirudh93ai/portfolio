# Anirudh Gupta - Personal Website

This is a professional personal website built with React, showcasing Anirudh Gupta's work as an AI Product Manager.

## Features

- ✨ **Professional Design**: Clean, modern interface with fluidic animations
- 🎯 **Interactive Elements**: Cursor-following effects and floating particles
- 📱 **Responsive Layout**: Optimized for desktop and mobile devices
- 🎨 **Smooth Animations**: Powered by Framer Motion for professional interactions
- 🔗 **LinkedIn Integration**: Direct links to professional profile
- 🤖 **AI Lab Showcase**: Highlighting AI projects, prototypes, and automations

## Deployment

### Quick Deploy Options

1. **Upload to any static hosting service:**
   - Netlify: Drag and drop the entire folder to Netlify
   - Vercel: Connect your repository or use the Vercel CLI
   - GitHub Pages: Upload files to your repository and enable GitHub Pages
   - AWS S3: Upload to an S3 bucket with static website hosting enabled

2. **For anirudhgupta.space domain:**
   - Upload all files to your web hosting provider's public_html or www directory
   - Ensure your DNS is configured to point to your hosting provider
   - The site will be available at https://anirudhgupta.space

### Local Preview

To preview the site locally before deployment:
```bash
npx serve .
```

### Important Notes

- Asset paths are relative (`./assets/`) and work from any hosting root
- The site works as a Single Page Application (SPA)
- Optimized for fast loading with minimal dependencies

### File Structure

```
static-site-download/
├── index.html          # Main HTML file
├── assets/
│   ├── index-*.css     # Compiled styles
│   └── index-*.js      # Compiled JavaScript
└── README.md           # This file
```

### Technical Details

- **Framework**: React 18 with TypeScript
- **Styling**: TailwindCSS with custom animations
- **Build Tool**: Vite for optimized production build
- **Icons**: Lucide React icons
- **Fonts**: Google Fonts (Inter) loaded via CDN
- **Animation Library**: Framer Motion

### Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

### SEO Features

- Proper meta tags for search engines
- Open Graph tags for social media sharing
- Semantic HTML structure
- Optimized performance with code splitting

### Support

For any issues or questions about deployment, please refer to your hosting provider's documentation or contact them directly.