# Public Directory

Place your background image for the Advent calendar here.

## Background Image

To set a background image for your calendar:

1. Add your image file to this directory (e.g., `background.jpg`, `background.png`)
2. Update the filename in `src/App.css`:

```css
.advent-calendar-bg {
  background-image: url('/background.jpg');
}
```

The image should ideally be:
- High resolution (1920x1080 or larger)
- Optimized for web (JPEG or PNG format)
- Considerate of the calendar overlay

If no image is provided, a gradient fallback will be used.

