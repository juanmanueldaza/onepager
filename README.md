# Onepager Site

A clean, single-page portfolio website showcasing professional information in a condensed format. Built with modern web standards and seamlessly integrated with the daza.ar ecosystem.

> **📁 Part of the daza.ar Ecosystem**: This repository is part of the [daza.ar-env](https://github.com/juanmanueldaza/daza.ar-env) development environment. For local development setup, unified workflow, and cross-site documentation, see the [main repository](https://github.com/juanmanueldaza/daza.ar-env).

## 🌐 Live Site

Visit the live onepager at: **[onepager.daza.ar](https://onepager.daza.ar)**

## ✨ Features

- 📱 **Fully Responsive** - Perfect display on all devices
- 📄 **PDF Export** - Download portfolio as PDF
- 🎨 **Clean Design** - Minimalist, professional styling
- ♿ **Accessible** - ARIA compliant with keyboard navigation
- 🚀 **Fast Loading** - Optimized performance
- 📝 **Markdown Content** - Content sourced from remote markdown files
- 🧭 **Integrated Navigation** - Uses the daza.ar navbar component
- 🔄 **Dynamic Updates** - Content updates from data repository
- 📊 **Condensed Format** - Key information in digestible sections

## 🏗️ Architecture

This onepager uses a **remote module architecture**:

- **Content**: Imported from [data.daza.ar](https://data.daza.ar/md/) markdown files
- **Navigation**: Uses [navbar.daza.ar](https://navbar.daza.ar) component
- **Markdown Processing**: Uses [mdsite.daza.ar](https://mdsite.daza.ar/mdsite.js) module
- **PDF Generation**: Integrated export functionality

## 🚀 Technology Stack

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with flexbox/grid
- **Vanilla JavaScript** - ES6 modules
- **Remote Modules** - Shared components from daza.ar ecosystem
- **GitHub Pages** - Static hosting with custom domain

## 📁 File Structure

```
onepager/
├── CNAME          # Custom domain configuration
├── index.html     # Main HTML file
└── README.md      # This file
```

## 🛠️ Development

### Local Development

Use the [daza.ar-env](https://github.com/juanmanueldaza/daza.ar-env) development environment:

```bash
# Clone the development environment
git clone https://github.com/juanmanueldaza/daza.ar-env.git
cd daza.ar-env

# Setup all sites (including this one)
./setup.sh

# Start development servers
./dev.sh

# Onepager site will be available at:
# http://onepager.local:3002
```

### Content Management

Content is managed centrally in the [data repository](https://github.com/juanmanueldaza/data):

1. Edit `one-pager.md` in the data repository
2. Changes reflect automatically on the live site
3. No deployment required for content updates

### Deployment

Automated deployment via GitHub Pages:

```bash
# Manual deployment (if needed)
npm run deploy
```

## 🎨 Customization

### Styling

Uses CSS custom properties for consistent theming:

```css
:root {
  --window-bg: #1a1a1a;
  --window-border: #333;
  --text-primary: #e0e0e0;
  --link: #4a9eff;
  --link-hover: #66b3ff;
}
```

### Content Sections

The onepager displays:

- **Profile Summary** - Brief professional overview
- **Key Skills** - Core competencies
- **Recent Experience** - Latest work highlights
- **Notable Projects** - Significant achievements
- **Contact Information** - Professional contacts

## 🔧 Configuration

Automatic configuration includes:

- **Navbar**: Professional contact links
- **PDF Export**: Optimized for printing
- **Content Loading**: Remote markdown processing
- **Accessibility**: Full WCAG compliance
- **SEO**: Meta tags and structured data

## 🏗️ Ecosystem Integration

This onepager is part of the **daza.ar ecosystem**:

- **🛠️ Development Environment**: [daza.ar-env](https://github.com/juanmanueldaza/daza.ar-env) - Unified development setup
- **📋 Contributing**: Follow the branch workflow in [daza.ar-env/CONTRIBUTING.md](https://github.com/juanmanueldaza/daza.ar-env/blob/main/CONTRIBUTING.md)
- **🎯 Issues & Features**: Use the [feature_improvement.md](https://github.com/juanmanueldaza/daza.ar-env/blob/main/.github/ISSUE_TEMPLATE/feature_improvement.md) template
- **🏗️ Architecture**: See [deployment documentation](https://github.com/juanmanueldaza/daza.ar-env/blob/main/docs/DEPLOYMENT.md)

### Related Sites

- **📄 CV Site**: [cv.daza.ar](https://cv.daza.ar) - Full detailed resume
- **🏠 Start Page**: [start.daza.ar](https://start.daza.ar) - Personal dashboard
- **🧭 Navbar**: [navbar.daza.ar](https://navbar.daza.ar) - Navigation component
- **📝 Mdsite**: [mdsite.daza.ar](https://mdsite.daza.ar) - Markdown processing utilities
- **📊 Data**: [data.daza.ar](https://data.daza.ar) - Content repository
- **🖼️ Wallpapers**: [wallpapers.daza.ar](https://wallpapers.daza.ar) - Wallpaper collection

## 📱 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers with responsive design

## 🤝 Contributing

Contributions welcome! Please use the unified development environment:

1. Use [daza.ar-env](https://github.com/juanmanueldaza/daza.ar-env) for development setup
2. Follow the [contributing guidelines](https://github.com/juanmanueldaza/daza.ar-env/blob/main/CONTRIBUTING.md)
3. Use the [feature template](https://github.com/juanmanueldaza/daza.ar-env/blob/main/.github/ISSUE_TEMPLATE/feature_improvement.md) for new features

### Content Contributions

- **Portfolio Content**: Edit `one-pager.md` in [data repository](https://github.com/juanmanueldaza/data)
- **Site Features**: Contribute to this repository or shared modules
- **Design**: Suggest UX/UI improvements

## 👤 Author

**Juan Manuel Daza**

- Website: [daza.ar](https://daza.ar)
- GitHub: [@juanmanueldaza](https://github.com/juanmanueldaza)
- LinkedIn: [juanmanueldaza](https://www.linkedin.com/in/juanmanueldaza)
- Email: juanmanueldaza@gmail.com

## 📄 License

MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <p>Made with ❤️ as part of the <a href="https://github.com/juanmanueldaza/daza.ar-env">daza.ar ecosystem</a></p>
  <p>
    <a href="https://onepager.daza.ar">Live Site</a> •
    <a href="https://github.com/juanmanueldaza/daza.ar-env">Development Environment</a> •
    <a href="https://github.com/juanmanueldaza/daza.ar-env/issues">Report Issue</a>
  </p>
</div>