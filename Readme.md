# 🌱 Plants - CSS Template

A fresh and modern CSS template designed for plant-related websites, e-commerce platforms, and nature-themed projects. Featuring a vibrant green color palette with minimalist and clean design principles.

## 📋 Overview

**Plants** is a customizable, ready-to-use CSS template perfect for:
- 🛒 Plant e-commerce websites
- 🌿 Gardening and plant care blogs
- 🏡 Home decoration platforms
- ♻️ Eco-friendly and sustainable projects

## 🎨 Color Palette

| Color Name | Hex Code | Usage |
|-----------|----------|-------|
| Mint Green | `#a6ebc9` | Primary accent |
| Bright Green | `#61ff7e` | Highlights & CTAs |
| Lime Green | `#5eeb5b` | Secondary highlights |
| Forest Green | `#62ab37` | Text & typography |
| Dark Gray | `#393424` | Background & dark elements |
| Brown | `#5c5235` | Borders & detail sections |

## 📁 Project Structure

```
plants/
├── index.html              # Main HTML file
├── Readme.md              # This file
├── styles/
│   ├── styles.css         # Main stylesheet
│   ├── fonts/
│   │   ├── fonts.css      # Font declarations
│   │   ├── Montserrat/    # Montserrat font files
│   │   └── Roboto/        # Roboto font files
│   └── uploads/           # Image assets
```

## 🚀 Getting Started

### 1. Installation
- Clone or download the project files
- No build process required—it's ready to use!

### 2. Basic Usage
```html
<link rel="stylesheet" href="styles/styles.css">
<link rel="stylesheet" href="styles/fonts/fonts.css">
```

### 3. File Structure
- Open `index.html` in your browser
- Edit HTML content as needed
- Customize colors in `styles/styles.css`

## 🎯 Key Features

### Typography
- **Montserrat**: Modern, clean sans-serif for headers and body text
- Multiple font weights (300-500) for flexibility
- Consistent sizing scale for visual hierarchy

### Components

#### Header Section
```html
<div class="header-title">
  <h1 class="first-title">Your Title</h1>
  <p class="first-p">Your subtitle</p>
</div>
```
Uses background image with dark overlay for depth.

#### Article Cards (Flexbox Layout)
```html
<div class="box-2">
  <div class="flexbox-x" id="sansevieria">
    <h2 class="white-standar-h2">Title</h2>
    <p class="white-standar-p">Description</p>
    <button class="white-button">Learn More</button>
  </div>
</div>
```

#### Call-to-Action Button
```html
<button class="white-button">Click Here</button>
```

## ✏️ Customization

### Changing Colors

Edit the CSS color values in `styles/styles.css`:

```css
html {
    background-color: #393424;  /* Change background */
}

.first-title {
    color: #fff;  /* Change text color */
}
```

### Modifying Typography

```css
.first-title {
    font-family: Montserrat;
    font-size: 50px;           /* Adjust size */
    font-weight: 500;          /* Adjust weight */
}
```

### Background Images

Replace image paths in `styles.css`:

```css
#sansevieria {
    background-image: linear-gradient(rgba(0, 0, 0, 0.4)), url(/your/new/image.jpg);
    background-size: cover;
    background-position: center;
}
```

## 🎓 CSS Classes Reference

### Headings

| Class | Font Size | Weight | Color | Purpose |
|-------|-----------|--------|-------|---------|
| `.white-standar-h2` | 30px | 400 | White | Primary heading |
| `.white-secondary-h2` | 24px | 400 | White | Secondary heading |

### Paragraphs

| Class | Font Size | Weight | Color | Purpose |
|-------|-----------|--------|-------|---------|
| `.white-standar-p` | 18px | 300 | White | Standard paragraph |
| `.white-secondary-p` | 16px | 300 | White | Secondary paragraph |

### Layout & Sections

| Class | Purpose |
|-------|---------|
| `.header-title` | Main header with background image & overlay |
| `.first-title` | Large primary heading (50px) |
| `.first-p` | Primary subtitle text (20px) |
| `.white-button` | Interactive button with hover effect |
| `.flexbox-x` | Flex column container for card layouts |
| `.box-2` | Two-column flex container with 20px gap |
| `.light_green_box` | Section with brown background (#5c5235) |
| `.horizontal-margin` | 50px horizontal padding wrapper |
| `.articles` | Container for article sections |

## 📝 Font Licenses

Both fonts included are licensed under the **SIL Open Font License (OFL)**:
- **Montserrat**: [OFL License](styles/fonts/Montserrat/OFL.txt)
- **Roboto**: [OFL License](styles/fonts/Roboto/OFL.txt)

You're free to use these fonts in commercial and personal projects!

## 💡 Tips for Customization

1. **Color Variables**: Create CSS variables for consistent theming
   ```css
   :root {
     --primary: #a6ebc9;
     --dark: #393424;
     --brown: #5c5235;
   }
   ```

2. **Responsive Design**: Add media queries for mobile optimization
   ```css
   @media (max-width: 768px) {
     .box-2 {
       flex-direction: column;
       height: auto;
     }
   }
   ```

3. **Add More Sections**: Duplicate and modify existing components
4. **Hover Effects**: Add transitions for smooth interactions
5. **Box Sizing**: Use `box-sizing: border-box;` when adding new elements

## 🤝 Contributing & Sharing

Feel free to:
- ✅ Use this template for personal projects
- ✅ Modify and customize for your needs
- ✅ Share with others (keep attribution)
- ✅ Fork and improve

## 📄 License

This template is free for personal and commercial use. The included fonts (Montserrat and Roboto) are licensed under the SIL Open Font License.

## 📧 Support

For issues or suggestions:
- Check the included font documentation
- Review the CSS comments for guidance
- Experiment with class combinations
- Write us an email explaining the context of the problem

---

**Version**: 1.0  
**Author**: Héctor Ixcamparic  
**Last Updated**: December 2025

Happy planting! 🌿