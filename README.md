# Interactive Image Gallery

A responsive image gallery with filtering and lightbox functionality built with HTML, CSS, and JavaScript.

## Features

- **Responsive Grid Layout**: Adapts to different screen sizes
- **Image Filtering**: Filter images by category (All, Nature, City, Animals)
- **Lightbox Viewer**: Click thumbnails to view larger versions
- **Navigation Controls**: 
  - Previous/Next buttons
  - Keyboard arrow keys support
  - Close button
- **Hover Effects**: Subtle animations on thumbnails
- **Accessibility**: Keyboard navigation and proper image alt text

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, transitions)
- JavaScript (DOM manipulation, event handling)

## Installation

No installation required. Simply:

1. Copy the code from `index.html`
2. Save it as an HTML file
3. Open in any modern web browser

## Usage

1. Click any thumbnail to open the lightbox view
2. In lightbox mode:
   - Use ← → arrow keys or on-screen buttons to navigate
   - Press ESC or click outside image to close
3. Use the filter buttons to show only specific categories

## Customization

To add your own images:

1. Replace the image URLs in the `galleryImages` array
2. Update the `alt` text and `category` for each image
3. Add new filter buttons if needed by copying the existing button HTML and updating the `data-filter` attribute

## Browser Support

The gallery works in all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: The demo uses Unsplash's random image API which requires an internet connection. For offline use, replace with local image paths.
