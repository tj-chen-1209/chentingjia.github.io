# Mingzhe Li's Academic Homepage

A modern, responsive academic website built with Jekyll and hosted on GitHub Pages.

## 🚀 Features

### ✨ New Features Added:
- **Modular Content Organization**: Content is organized into separate modules for easy maintenance
- **Beautiful Paper Display**: Enhanced paper presentation with images, badges, and statistics
- **News & Updates**: Dynamic news section for sharing latest achievements
- **Google Scholar Integration**: Automatic citation statistics (when configured)
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Professional Styling**: Custom CSS with paper-box layouts and modern aesthetics

### 📂 Content Modules:
- **Introduction**: Personal and research overview
- **News**: Latest updates and achievements
- **Publications**: Research papers with enhanced display
- **Education**: Academic background and achievements
- **Projects**: Research and open-source projects
- **Services**: Academic activities and community involvement

## 🛠️ Setup Instructions

### Prerequisites:
- Ruby (2.7.0 or higher)
- Jekyll
- GitHub account

### Local Development:
```bash
# Clone the repository
git clone https://github.com/Mubuky/mubuky.github.io.git
cd mubuky.github.io

# Install dependencies
bundle install

# Run locally
bundle exec jekyll serve
```

### Deployment:
The site automatically deploys to GitHub Pages when changes are pushed to the main branch.

## 📝 Customization Guide

### Personal Information:
Edit `_config.yml` to update:
- Personal details (name, bio, location)
- Social media links
- Google Scholar settings

### Content Updates:
All content modules are located in `_pages/includes/`:
- `intro.md` - Personal introduction
- `news.md` - Latest news and updates
- `pub.md` - Research publications
- `education.md` - Academic background
- `projects.md` - Research and personal projects
- `services.md` - Academic services

### Adding Publications:
1. Add paper details to `pub.md`
2. Include paper image in `/images/` directory
3. Use the `paper-box` layout for enhanced display

### Google Scholar Stats:
1. Enable in `_config.yml`: `google_scholar_stats_use_cdn: true`
2. Generate stats using the provided crawler script
3. Upload stats to `google-scholar-stats/gs_data.json`

## 🎨 Styling

The website uses custom CSS with:
- **Paper-box layout** for research publications
- **Responsive design** for all screen sizes
- **Modern typography** and color scheme
- **Smooth animations** and transitions

## 📊 Analytics & Stats

- Google Scholar citation tracking
- GitHub repository statistics
- Visitor analytics (when configured)

## 🔧 Technical Details

- **Framework**: Jekyll 4.x
- **Theme**: Based on Minimal Mistakes (heavily customized)
- **Hosting**: GitHub Pages
- **CSS**: SCSS with custom components
- **Icons**: Font Awesome
- **Responsive**: Bootstrap-inspired grid system

## 📄 License

This project is licensed under the MIT License. Feel free to use it as a template for your own academic website.

## 🤝 Contributing

Suggestions and improvements are welcome! Please feel free to:
1. Open an issue for bugs or feature requests
2. Submit a pull request for improvements
3. Share your customizations with the community

## 📧 Contact

**Mingzhe Li**  
📧 Email: mzli@ir.hit.edu.cn  
🔗 Website: https://mubuky.github.io  
🎓 Institution: Harbin Institute of Technology

---

*Last updated: January 2025*