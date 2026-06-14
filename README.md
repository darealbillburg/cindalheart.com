# Cindalheart.com

A beautiful, accessible static website built with clean HTML and CSS.

## 📁 Folder Structure

```
cindalheart.com/
├── index.html              # Homepage
├── css/
│   └── style.css          # Main stylesheet
├── pages/
│   ├── about.html         # About page
│   └── contact.html       # Contact page
├── images/                # Place images here (optional)
├── js/                    # Place JavaScript files here (optional)
└── README.md              # This file
```

## 🚀 Getting Started

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/darealbillburg/cindalheart.com.git
   cd cindalheart.com
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (if http-server is installed)
   http-server
   ```

3. Visit `http://localhost:8000` in your browser

### Deployment
This site is deployed using **GitHub Pages** and is automatically live at:
- **URL:** https://darealbillburg.github.io/cindalheart.com

Any changes pushed to the `main` branch will be automatically deployed.

## ✨ Features

- **Responsive Design** - Works perfectly on all devices
- **Accessible** - Built with semantic HTML and accessibility best practices
- **Fast** - Static HTML means lightning-fast load times
- **No Dependencies** - Pure HTML and CSS, no frameworks required
- **SEO Friendly** - Proper meta tags and semantic markup

## 📝 Customization

### Changing Colors
Edit the CSS variables in `css/style.css`:
```css
:root {
    --primary-color: #6b4fa3;
    --secondary-color: #d4528f;
    /* ... */
}
```

### Adding New Pages
1. Create a new HTML file in the `pages/` directory
2. Copy the structure from `about.html` or `contact.html`
3. Update the navigation links in all pages

### Adding Images
1. Create an `images/` folder
2. Add your images there
3. Reference them: `<img src="../images/my-image.jpg" alt="Description">`

## 🔧 Tools & Technologies

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **GitHub Pages** - Free hosting

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

Created by [darealbillburg](https://github.com/darealbillburg)

---

**Happy building! 🎉**
