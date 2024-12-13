# Pizza Website

This repository contains the code for a visually appealing and fully responsive pizza website built using modern web technologies. The website is designed to showcase pizza offerings with an interactive and user-friendly interface.

## Features

- **Dynamic UI**: Built with vanilla JavaScript for dynamic interactions.
- **Smooth Animations**: Integrated using [Swiper.js](https://swiperjs.com/) for carousels and scrolling effects.
- **Optimized Scrolling**: Enhanced scrolling effects implemented via `scroll-bundler`.
- **Responsive Design**: Fully responsive across all devices, thanks to thorough use of CSS variables and comprehensive media queries.
- **Thematic Styling**: Utilized CSS variables to maintain consistent theming throughout the website.

---

## Technology Stack

1. **HTML5** - Semantic and structured content.
2. **CSS3** - Advanced styling with CSS variables and animations.
3. **JavaScript (ES6+)** - Adding interactivity and dynamic behavior.
4. **Swiper.js** - For implementing carousels and sliders.
5. **Scroll-bundler** - Enhancing scrolling functionalities.

---

## Installation

### Prerequisites
- A modern browser (e.g., Chrome, Firefox, Safari).
- Local server setup (optional for local testing, e.g., Live Server extension in VS Code).

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/sainiayush/PizzaBest.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pizza-website
   ```
3. Open `index.html` in your browser to view the website.

---

## Folder Structure

```
root/
├── index.html        # Main HTML file
├── js/
│   ├── main.js    # Main JavaScript file
│   ├── swiper-bundle-min.js    # Swiper.js integration
│   ├── scrollreveal.min.js    # Interactive Scroller animations
└── assets/          # Additional resources
    └──
      css/
      │   ├── styles.css   # Main stylesheet
      │   ├── swiper-bundle.min.css     # Swiper.css integration
      js/
      │   ├── main.js    # Main JavaScript file
      │   ├── swiper-bundle-min.js    # Swiper.js integration
      │   ├── scrollreveal.min.js    # Interactive Scroller animations
      │
      images/          # Folder for all images
```

---

## Guidelines Followed

1. **Semantic HTML**:
   - Used semantic tags like `<header>`, `<main>`, `<footer>`.
2. **CSS Best Practices**:
   - Variables are defined in `main.css` for easy customization.
   - BEM methodology for class naming.
3. **JavaScript Best Practices**:
   - Modular functions for reusability.
   - Clear and concise comments.
4. **Performance**:
   - Optimized images for faster load times.
   - Minimized JavaScript and CSS files.

---

## Media Queries

Extensive media queries were implemented to ensure responsiveness across devices:

```css
/* Mobile devices */
@media (max-width: 576px) {
  body{
    box-sizing: border-box;
    padding: 0;
    margin: 0;
  }

/* Tablets */
@media (min-width: 768px) {
  .contact__container{
    width: 450px;
    margin-inline: auto;
  }

  .footer__form{
    width: 360px;
  }
}

/* Large screens */
@media (min-width: 1150px) {
  .popular__swiper{
    width: 600px;
    overflow-x: clip;
    justify-self: center;
  }

  .products__container{
    grid-template-columns: repeat(3, 160px);
  }
}
```

---

## Future Enhancements

- Add a cart system with localStorage.
- Integrate a backend for order processing.
- Add multi-language support.

---

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for review.

---
