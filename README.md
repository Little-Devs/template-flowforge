# FlowForge - Technical Luxury Landing Page Template

A sophisticated, production-ready landing page template for automation platforms, SaaS products, and developer tools. Built with Astro and featuring a distinctive "Technical Luxury" aesthetic.

![FlowForge Template](https://img.shields.io/badge/Astro-5.17.1-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

- **Technical Luxury Aesthetic** - Refined design with deep navy, warm copper accents, and elegant typography
- **Smooth Animations** - Parallax effects, scroll-triggered reveals, and micro-interactions
- **Fully Responsive** - Mobile-first design that works beautifully on all devices
- **Production Ready** - Clean, semantic code with organized CSS architecture
- **Fast Performance** - Astro SSG with CSS-only animations for optimal load times
- **Easy Customization** - CSS variables for colors, spacing, and typography

## 🎨 Design System

### Typography
- **Display Font**: Fraunces (elegant serif for headlines)
- **Sans Font**: Syne (refined sans-serif for body)
- **Mono Font**: JetBrains Mono (code examples)

### Color Palette
- **Primary**: Navy (#0a1628) - Deep, sophisticated base
- **Accent**: Copper (#d4a574) - Warm, luxurious highlights
- **Background**: Off-white (#faf9f7) - Soft, refined canvas

### Components
- Animated hero with parallax background
- Feature cards with hover effects
- Syntax-highlighted code window
- Glassmorphic navigation
- Social proof logos
- CTA sections
- Professional footer

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ and npm

### Installation

```bash
# Clone the repository
git clone https://github.com/Little-Devs/template-flowforge.git
cd template-flowforge

# Install dependencies
npm install

# Start development server
npm run dev
```

The site will be available at `http://localhost:4321/`

### Build for Production

```bash
# Build static site
npm run build

# Preview production build
npm run preview
```

## 📁 Project Structure

```
/
├── public/              # Static assets
│   ├── favicon.ico
│   └── favicon.svg
├── src/
│   ├── pages/
│   │   └── index.astro  # Main landing page
│   └── styles/
│       └── global.css   # Global styles and design system
├── astro.config.mjs     # Astro configuration
├── package.json
├── template.json        # Template metadata
└── README.md
```

## 🎯 Customization Guide

### Colors

Edit CSS variables in `src/styles/global.css`:

```css
:root {
  --color-navy-900: #0a1628;     /* Primary color */
  --color-copper-500: #d4a574;   /* Accent color */
  --color-off-white: #faf9f7;    /* Background */
  /* ... more variables */
}
```

### Typography

Change fonts in `src/pages/index.astro` (Google Fonts link):

```html
<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT&display=swap" rel="stylesheet">
```

Then update CSS variables:

```css
:root {
  --font-display: 'YourFont', serif;
  --font-sans: 'YourFont', sans-serif;
}
```

### Content

Edit text content directly in `src/pages/index.astro`:

- Hero section (lines 20-80)
- Features grid (lines 82-130)
- Platform showcase (lines 132-180)
- CTA and footer (lines 200+)

### Sections

The template includes these sections:

1. **Navigation** - Fixed glassmorphic nav
2. **Hero** - Animated headline, CTA, and stats
3. **Features** - 6-card grid with hover effects
4. **Platform** - Split layout with code window
5. **Social Proof** - Company logos
6. **CTA** - Final call-to-action
7. **Footer** - Links and legal

Remove or rearrange sections as needed.

## 🎬 Animations

All animations are implemented with CSS for optimal performance:

- **Parallax** - Hero background moves on scroll
- **Scroll-triggered** - Cards fade in when visible
- **Hover effects** - Cards lift and scale
- **Staggered reveals** - Headlines animate in sequence
- **Micro-interactions** - Button hovers, icon floats

Control animation timing in CSS variables:

```css
--transition-fast: 0.15s;
--transition-base: 0.3s;
--transition-slow: 0.5s;
```

## 📱 Responsive Breakpoints

- **Desktop**: 1024px+
- **Tablet**: 768px - 1023px
- **Mobile**: < 768px

Responsive styles are at the bottom of `global.css`.

## 🎨 Use Cases

Perfect for:

- SaaS platforms and automation tools
- Developer tools and APIs
- B2B software services
- Workflow and productivity apps
- Enterprise solutions
- Technical products

## 🔧 Tech Stack

- **Framework**: [Astro](https://astro.build) v5.17.1
- **Styling**: Vanilla CSS with CSS Variables
- **Fonts**: Google Fonts (Fraunces, Syne, JetBrains Mono)
- **Build**: Astro SSG (Static Site Generation)

## 📄 License

MIT License - feel free to use for personal or commercial projects.

## 🤝 Contributing

This template is part of the [Little-Devs Web Templates](https://github.com/Little-Devs/web-templates) collection.

To suggest improvements:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## 💡 Tips

- **Performance**: Keep animations CSS-only when possible
- **Accessibility**: Maintain color contrast ratios (WCAG AA)
- **SEO**: Update meta tags and title in `index.astro`
- **Images**: Optimize images before adding to `public/`
- **Testing**: Test on multiple browsers and devices

## 🆘 Support

For issues or questions:
- Open an issue on GitHub
- Check [Astro documentation](https://docs.astro.build)
- Review the template metadata in `template.json`

## 🌟 Showcase

Built with this template? We'd love to see it! Tag [@Little-Devs](https://github.com/Little-Devs) or open a PR to add your site to our showcase.

---

**Made with ⚡ by Little-Devs**
