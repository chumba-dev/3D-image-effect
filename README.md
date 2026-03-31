# 3D Blog Carousel Hero Section

A stunning, interactive 3D hero section designed for a modern digital publishing platform ("The Brief"). This project features a 3D rotating carousel of blog posts orbiting around a static central element (e.g., a branded globe).

## Features

- **3D Rotating Carousel:** Smooth infinite rotation built with CSS 3D transforms (`perspective`, `rotateY`, `translateZ`) allowing item cards to orbit around the center.
- **Center Globe Integration:** A placeholder globe fixed in the 3D space (`transform-style: preserve-3d`) intersecting naturally with the rotating items.
- **Atmospheric Effects:** Background CSS sparkles and a grid backdrop paired with an oversized watermark.
- **Fully Responsive:** Adapts beautifully across Desktop, Tablet, and Mobile views, dynamically adjusting both the individual items and the carousel radius scaling.

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/chumba-dev/3D-image-effect.git
   cd 3D-image-effect
   ```

2. **Add Your Custom Central Image:**
   By default, the `hero-section.html` is looking for a file named `globe.png` located directly in the root directory. To substitute it with your custom globe or central object:
   - Place your image in the project folder.
   - Rename it to `globe.png` **OR** update line 27 of `hero-section.html` to point to your specific image filename (e.g., `src="custom-globe.jpg"`).

3. **Run Locally:**
   Simply open `hero-section.html` in any web browser of your choice.

## Technologies Used

- **HTML5** Document Structuring and semantic UI.
- **Vanilla CSS3** Animations, layout properties, media queries, and 3D perspectives.
- **Vanilla JavaScript** Dynamic generation of carousel slider items and dynamic sparkle effects.
