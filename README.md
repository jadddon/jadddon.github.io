# Personal Portfolio Website

A minimalist portfolio website showcasing work in data science, software engineering, and digital art.

## Features

- **Minimalist Design**: Clean, content-focused layout with lots of white space
- **Video Backgrounds**: Hero section with video background support
- **Project Showcases**: Dedicated sections for each project with video demos
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Smooth Animations**: Subtle scroll-triggered animations and transitions
- **Performance Optimized**: Lazy loading videos and optimized assets

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Custom Properties)
- Vanilla JavaScript
- Intersection Observer API
- CSS Animations & Transitions

## Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in your browser
3. Or use a local server (recommended):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

### Adding Your Content

1. **Personal Information**:
   - Update name, title, and description in `index.html`
   - Replace contact links with your actual social media profiles

2. **Projects**:
   - Replace project descriptions, technologies, and links
   - Add your project videos to the `videos/` folder
   - Update video sources in the HTML

3. **Background Video**:
   - Add `hero-background.mp4` to the `videos/` folder
   - Recommended: 10-30 seconds, 1920x1080, under 10MB

4. **Styling**:
   - Customize colors, fonts, and spacing in `css/style.css`
   - Adjust video overlay opacity for different aesthetics

## File Structure

```
portfolio-website/
├── index.html              # Main HTML file
├── css/
│   └── style.css          # All CSS styles
├── js/
│   └── script.js          # JavaScript functionality
├── videos/
│   ├── hero-background.mp4    # Hero section background video
│   ├── project1-demo.mp4      # Project demo videos
│   ├── project2-demo.mp4
│   └── ...
├── images/
│   ├── projects/          # Project screenshots/images
│   └── profile/           # Profile images
├── README.md              # Project documentation
└── .gitignore            # Git ignore rules
```

## Deployment

### GitHub Pages (Recommended)

1. Create a repository named `yourusername.github.io`
2. Push your code to the repository
3. Your site will be available at `https://yourusername.github.io`

### Alternative Hosting Options

- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **Surge.sh**: Simple static hosting

## Video Optimization Tips

### Hero Background Video
- **Duration**: 10-30 seconds (loops seamlessly)
- **Resolution**: 1920x1080 or 1920x1200
- **Format**: MP4 (H.264 codec)
- **File Size**: Under 10MB for fast loading
- **Content**: Subtle, non-distracting visuals

### Project Demo Videos
- **Duration**: 30-60 seconds
- **Resolution**: 1920x1080
- **Format**: MP4
- **File Size**: Under 20MB each
- **Content**: Clear demonstrations of your work

### Video Compression
Use tools like:
- **HandBrake** (free)
- **FFmpeg** (command line)
- **Adobe Media Encoder**
- **Online converters** for smaller files

## Customization Guide

### Colors
The design uses a minimal color palette. To customize:

```css
/* Main text color */
color: #2c2c2c;

/* Secondary text */
color: #666;

/* Light text */
color: #999;

/* Very light text */
color: #ccc;
```

### Typography
The site uses system fonts for performance:
```css
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
```

### Video Overlay
Adjust the hero video overlay:
```css
.hero-overlay {
    background: rgba(255, 255, 255, 0.85); /* White overlay */
    /* or */
    background: rgba(0, 0, 0, 0.4); /* Dark overlay */
}
```

## Performance Features

- **Lazy Loading**: Videos only play when in viewport
- **Optimized Animations**: Uses `transform` and `opacity` for 60fps
- **Minimal JavaScript**: Vanilla JS, no heavy frameworks
- **Efficient CSS**: Uses modern layout methods (Grid, Flexbox)

## Browser Support

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- Mobile browsers: Full support

## Contributing

Feel free to fork this project and customize it for your own use. If you make improvements, pull requests are welcome!

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

- Website: [yourdomain.com](https://yourdomain.com)
- Email: your.email@domain.com
- LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)
- GitHub: [github.com/yourusername](https://github.com/yourusername)