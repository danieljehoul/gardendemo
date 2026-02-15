# Assets Directory

This folder contains all static assets for the Mali Vrtlari website.

## Folder Structure

```
assets/
├── images/     # Image files (PNG, JPG, SVG, etc.)
├── css/        # Additional CSS files
├── js/         # JavaScript files
└── fonts/      # Custom font files
```

## Usage Guidelines

### Images (`assets/images/`)
Store all image files here:
- Logo files
- Garden project photos
- Service illustrations
- Icons and graphics
- Background images

**Example usage in HTML:**
```html
<img src="assets/images/logo.png" alt="Mali Vrtlari Logo">
```

### CSS (`assets/css/`)
Additional stylesheets beyond the main `assets/css/styles.css`:
- Theme variations
- Component-specific styles
- Vendor CSS files

**Example usage in HTML:**
```html
<link rel="stylesheet" href="assets/css/gallery.css">
```

### JavaScript (`assets/js/`)
JavaScript files for interactive features:
- Image galleries
- Form validation
- Animations
- Third-party libraries

**Example usage in HTML:**
```html
<script src="assets/js/gallery.js"></script>
```

### Fonts (`assets/fonts/`)
Custom web fonts:
- WOFF/WOFF2 files
- TTF/OTF files

**Example usage in CSS:**
```css
@font-face {
    font-family: 'CustomFont';
    src: url('../fonts/customfont.woff2') format('woff2');
}
```

## Best Practices

1. **Organize by type** - Keep images, CSS, JS, and fonts in their respective folders
2. **Use descriptive names** - e.g., `garden-landscaping-project-1.jpg` instead of `img1.jpg`
3. **Optimize images** - Compress images before uploading to improve page load times
4. **Version control** - All assets should be committed to the repository
5. **Relative paths** - Use relative paths from the HTML file location

## Image Optimization Tips

- Use appropriate formats: JPEG for photos, PNG for graphics with transparency, SVG for logos
- Compress images to reduce file size
- Consider using responsive images with multiple sizes
- Add descriptive `alt` text for accessibility

