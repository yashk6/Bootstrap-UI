# Complex UI Website Project

A responsive, visually appealing, and accessible webpage built strictly using **HTML5**, **CSS3**, and **Bootstrap 5.3**.

---

## 🌟 Project Features

1. **Responsive Header & Navigation Bar (`Part 1`)**
   - Heading/Brand: `Complex UI`
   - Navigation Links: `Section 1`, `Section 2`, `Section 3`
   - Search bar with placeholder and styled search button (`btn-outline-success`)
   - Responsive hamburger toggler for smaller screen sizes

2. **Bootstrap Carousel (`Part 2`)**
   - High-resolution background images with captions and Call-to-Action buttons
   - Prev/Next navigation controls and slide indicators
   - Smooth slide transitions (`carousel-fade`)

3. **Custom Flex Section (`Part 3`)**
   - CSS Flexbox container housing three equal-width divs
   - `300 x 200` aspect ratio images with centered descriptions
   - Responsive flex-wrap behavior for mobile viewports

4. **CSS Grid Photo Gallery (`Part 4`)**
   - 3-row photo gallery displaying 9 responsive images
   - Custom layout matching the Figma design:
     - Left tall image spanning 2 rows
     - 6 middle and right grid items
     - Bottom row split with left image and wide right image
   - Aspect ratios and responsiveness preserved via CSS Grid media queries

5. **Bootstrap Cards Section (`Part 5`)**
   - 3 Bootstrap cards transitioning from a 3-column row to a 1-column stack on small screens
   - Custom drop shadows (`box-shadow`) applied to cards
   - Smooth hover animations and elevation effects on Call-to-Action buttons

6. **Bootstrap Footer (`Part 6`)**
   - 3 columns: `Useful Links`, `More Links`, `Contact Us`
   - Copyright notice on bottom left
   - `Back to Top` button on bottom right with smooth scrolling (`html { scroll-behavior: smooth; }`)

---

## 📁 File Structure

```
d:/Bootstrap Ui/
├── index.html        # Main HTML5 structure with Bootstrap 5 CDN
├── styles.css        # Custom CSS for Flexbox, CSS Grid, animations, & responsiveness
└── README.md         # Project documentation & deployment guide
```

---

## 🚀 How to Run Locally

1. Double-click or open `index.html` in any web browser (Chrome, Firefox, Edge, Safari).
2. Or use any local static web server (such as VS Code Live Server).

---

## 🌐 Deployment Instructions (GitHub Pages & Netlify)

### GitHub Pages:
1. Initialize git and commit:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of Complex UI website"
   ```
2. Create a new GitHub repository and push:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```
3. In GitHub repo settings, navigate to **Pages** > Select `main` branch > Click **Save**.

### Netlify:
1. Drag and drop the `Bootstrap Ui` folder into [Netlify Drop](https://app.netlify.com/drop) for instant deployment.
