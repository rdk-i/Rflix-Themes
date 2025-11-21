# Rflix Themes

![Version](https://img.shields.io/badge/version-1.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Jellyfin](https://img.shields.io/badge/Jellyfin-10.8+-purple)

A custom theme for Jellyfin media server based on ElegantFin with Rflix branding and UI enhancements.

## ✨ Features

- **Modern Dark Theme** - Beautiful dark color scheme based on ElegantFin v25.10.27
- **Custom Branding** - Rflix logo and branding throughout the interface
- **Enhanced Login Page** - Cleaner login experience with hidden elements
- **Fixed Play Buttons** - Improved square play button appearance
- **Material Icons Round** - Modern rounded icon set
- **Responsive Design** - Optimized for desktop, mobile, and TV layouts
- **Customizable Variables** - Easy theming through CSS variables

## 🎨 What's Included

### Base Theme (ElegantFin v25.10.27)

- Comprehensive dark theme with gradient backgrounds
- Card hover effects and animations
- Responsive media queries for all screen sizes
- Custom font integration (Inter)
- Blur effects and modern UI elements

### Rflix Customizations

- **Hidden Elements**:
  - "Forgot Password" button on login page
  - "My Media" section title
  - Login page header (shown after login)
  - "Please sign in" text
- **Custom Logo**: Rflix branding in admin drawer and page titles

### UI Fixes

- Square play button with proper sizing (2.75em)
- Centered button content
- Hidden play text for cleaner appearance
- Consistent button alignment

## 📦 Installation

### Method 1: Direct CSS Link (Recommended)

1. Go to **Jellyfin Dashboard** → **General** → **Custom CSS**
2. Add the following URL:
   ```
   https://raw.githubusercontent.com/rdk-i/Rflix-Themes/main/rflix-themes-1.0.css
   ```
3. Click **Save**
4. Refresh your Jellyfin page

### Method 2: Local Installation

1. Download `rflix-themes-1.0.css` from this repository
2. Go to **Jellyfin Dashboard** → **General** → **Custom CSS**
3. Copy and paste the entire CSS file content
4. Click **Save**
5. Refresh your Jellyfin page

## 🎯 Customization

The theme uses CSS variables for easy customization. Edit these values at the top of the CSS file:

### Colors

```css
--darkerGradientPoint: #111827;
--lighterGradientPoint: #1d2635;
--activeColor: rgb(119, 91, 244);
--btnMiniPlayColor: rgb(41 154 93);
```

### Logo URLs

```css
/* Change these URLs to use your own logo */
.adminDrawerLogo img {
  content: url(YOUR-LOGO-URL) !important;
}
.imgLogoIcon {
  content: url(YOUR-LOGO-URL) !important;
}
.pageTitleWithLogo {
  background-image: url(YOUR-LOGO-URL) !important;
}
```

### Other Options

```css
/* Card hover effect: "" to enable, none to disable */
--cardHoverEffect: "";

/* App bar height: 5em for fading, 4.6em for solid */
--appBarHeight: 5em;

/* Icon pack: 'Material Icons Round' or 'Material Icons' */
--iconPack: "Material Icons Round", Material Icons;
```

## 📸 Screenshots

> Add your screenshots here showing the theme in action:
>
> - Login page
> - Home page
> - Media detail page
> - Mobile view

## 🔧 Component Files

If you want to customize specific parts, the theme is built from these components:

- `rflix-ElegantFin-theme-v25.10.27.css` - Base ElegantFin theme
- `rflix-branding-custom.css` - Rflix branding customizations
- `jellyfin_fix_button_play.css` - Play button fixes

All combined into: **`rflix-themes-1.0.css`**

## 📝 Browser Compatibility

- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers
- ✅ Jellyfin Android/iOS apps
- ✅ Android TV / Apple TV

## 🐛 Known Issues

- None currently. Please report any issues you encounter!

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 Credits

- **Base Theme**: [ElegantFin](https://github.com/lscambo13/ElegantFin) by lscambo13
- **Font**: [Inter](https://fonts.google.com/specimen/Inter) by Rasmus Andersson
- **Icons**: [Material Symbols Rounded](https://fonts.google.com/icons) by Google

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Support

If you like this theme, please give it a ⭐ on GitHub!

## 📞 Contact

- GitHub Issues: [Report a bug or request a feature](https://github.com/rdk-i/Rflix-Themes/issues)
- Discussions: [Ask questions or share ideas](https://github.com/rdk-i/Rflix-Themes/discussions)

---
