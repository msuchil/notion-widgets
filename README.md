# The Widget Studio

A minimal, beige-toned website for showcasing and selling Notion widgets and templates.

## Pages
- `index.html` — Home page
- `about.html` — About the maker
- `widgets.html` — Notion Widgets shop
- `templates.html` — Notion Templates shop

## Publishing to GitHub Pages

1. Create a new GitHub repository (e.g. `widget-studio`)
2. Upload all files in this folder to the repo root
3. Go to **Settings → Pages**
4. Under **Source**, select `main` branch and `/ (root)`
5. Click **Save** — your site will be live at `https://yourusername.github.io/widget-studio/`

## Customizing

### Your name & photo
- Open `about.html` and replace `[Your Name]` with your actual name
- Replace the portrait placeholder div with: `<img src="your-photo.jpg" alt="Your Name" style="width:100%;height:100%;object-fit:cover;">`

### Your products
- Edit the product cards in `widgets.html` and `templates.html`
- Update `href="#"` links on each **Get it / Buy** button with your actual Gumroad, Lemon Squeezy, or Notion link

### Site name
- Do a find-and-replace of `The Widget Studio` with your preferred brand name across all `.html` files

### Colors
- All colors are CSS variables at the top of `style.css` — easy to adjust

## File structure
```
/
├── index.html
├── about.html
├── widgets.html
├── templates.html
├── style.css
├── nav.js
└── README.md
```
