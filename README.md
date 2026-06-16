# FitLife Gym

A modern, professional fitness website built with HTML, CSS, and Font Awesome.

![FitLife Gym Preview](https://images.unsplash.com/photo-1534438327276-14e5300c3a48?w=1200)

## Features

- **Professional Design**: Clean, modern UI with a dark theme and accent colors
- **Multi-Page Structure**: Separate pages for Home, Programs, Trainers, About, and Contact
- **Responsive Layout**: Fully responsive design that works on all screen sizes
- **Interactive Elements**: Hover effects, smooth transitions, and modern card designs
- **Icons & Typography**: Google Fonts (Poppins) and Font Awesome for a polished look
- **Modern CSS**: Uses Flexbox, CSS Grid, and CSS variables for easy customization

## Pages Included

1. **Home (index.html)**: Hero section, about overview, and newsletter signup
2. **Programs (programs.html)**: Grid of fitness programs with images and descriptions
3. **Trainers (trainers.html)**: Profiles of expert coaching staff
4. **About (about.html)**: Gym history, mission, and core values
5. **Contact (contact.html)**: Contact form, location details, and business hours

## Technologies Used

- **HTML5**: Semantic markup for better accessibility and SEO
- **CSS3**: Modern styling with Flexbox, Grid, and animations
- **Google Fonts (Poppins)**: Clean, modern typography
- **Font Awesome**: Professional icon library
- **Unsplash**: High-quality fitness imagery

## Getting Started

### Installation

No installation required! Simply open the HTML files in your browser.

```bash
# Clone the repository
cd /path/to/lamin
```

### Usage

Open `index.html` in your browser, or serve locally with a simple HTTP server:

```bash
# Using Python 3
python3 -m http.server 8000

# Then open your browser and go to:
# http://localhost:8000
```

## File Structure

```
Lamin/
├── index.html          # Home page
├── programs.html       # Programs page
├── trainers.html       # Trainers page
├── about.html          # About page
├── contact.html        # Contact page
├── style.css           # Global styles
└── README.md           # This file
```

## Customization

### Colors

Colors are defined as CSS variables in `style.css` for easy customization:

```css
:root {
    --primary-color: #ef4444;    /* Crimson Red */
    --primary-hover: #dc2626;    /* Darker Red */
    --secondary-color: #1f2937;  /* Charcoal */
    --bg-dark: #111827;          /* Dark Slate */
    --bg-darker: #0f172a;        /* Very Dark */
    --text-light: #f8fafc;       /* Off-White */
    --text-muted: #94a3b8;       /* Light Gray */
}
```

### Typography

The website uses **Poppins** from Google Fonts. You can change the font in the `<head>` section of each HTML file:

```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
```

## Credits

- **Images**: [Unsplash](https://unsplash.com)
- **Icons**: [Font Awesome](https://fontawesome.com)
- **Typography**: [Google Fonts](https://fonts.google.com)

## License

MIT License - feel free to use this project for personal or commercial purposes.

## Contact

For questions or feedback, reach out at **fitlifegym@gmail.com**

---

Made with ❤️ and 💪 by FitLife Gym
