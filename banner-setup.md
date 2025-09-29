# How to Add Your Banner Photo

## Option 1: Use a Local Image (Recommended)

1. **Add your photo** to the `images/` folder (e.g., `images/banner-photo.jpg`)

2. **Update the CSS** in `style.css` around line 45, replace this line:
   ```css
   background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), 
               url('https://images.unsplash.com/photo-1518709268805-4e9042af2176?ixlib=rb-4.0.3&auto=format&fit=crop&w=2000&q=80') center/cover;
   ```
   
   **With:**
   ```css
   background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), 
               url('images/banner-photo.jpg') center/cover;
   ```

## Option 2: Use Different Stock Photos

Replace the URL in the CSS with any of these high-quality tech photos:

### Tech/Business Photos:
- `https://images.unsplash.com/photo-1451187580459-43490279c0fa?ixlib=rb-4.0.3&auto=format&fit=crop&w=2000&q=80` (Tech workspace)
- `https://images.unsplash.com/photo-1518709268805-4e9042af2176?ixlib=rb-4.0.3&auto=format&fit=crop&w=2000&q=80` (Modern tech)
- `https://images.unsplash.com/photo-1560472354-b33ff0c44a43?ixlib=rb-4.0.3&auto=format&fit=crop&w=2000&q=80` (Gadgets)

### Clean/Minimal Photos:
- `https://images.unsplash.com/photo-1557804506-669a67965ba0?ixlib=rb-4.0.3&auto=format&fit=crop&w=2000&q=80` (Minimal setup)
- `https://images.unsplash.com/photo-1516321318423-f06f85e504b3?ixlib=rb-4.0.3&auto=format&fit=crop&w=2000&q=80` (Clean desk)

## Current Setup

The banner currently uses:
- **Black overlay** (70% opacity) over the photo for text readability
- **Responsive design** that works on all devices
- **High-quality photo** from Unsplash showing modern tech

## Tips for Best Results

1. **Image Size**: Use images at least 1920x1080px for best quality
2. **Format**: JPG or PNG works best
3. **Content**: Choose images that complement your black and white theme
4. **Contrast**: The dark overlay ensures white text is always readable

## File Location

The banner CSS is located in `style.css` starting around line 44 in the `.banner` selector.
