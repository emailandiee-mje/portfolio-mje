# Miranda Jane Ellison | Analytics Engineer Portfolio

Modern glassmorphism portfolio showcasing expertise in serverless data infrastructure, analytics engineering, and full-stack development with a commitment to inclusive design and LGBTQ+ community support.

## 🚀 Quick Start

### Prerequisites
- Git (https://git-scm.com/download/win)
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools required!

### Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/emailandiee-mje/portfolio-mje.git
   cd portfolio-mje
   ```

2. **View the Portfolio**
   - Simply open `index.html` in your web browser
   - Uses Tailwind CSS CDN - no build process needed
   - All dependencies loaded via CDN (Tailwind, Font Awesome, Google Fonts)

3. **Deploy to GitHub Pages**
   - Push to the `main` branch
   - Go to repository Settings → Pages
   - Select `main` branch as the source
   - Your site will be live at `https://emailandiee-mje.github.io/portfolio-mje/`

## 📂 Project Structure

```
portfolio-mje/
├── index.html              # Complete portfolio website (glassmorphism bento grid)
├── PROJECT_PLAN.md         # Original project specification (archived)
├── README.md               # This file
├── .gitignore              # Git ignore rules
├── assets/                 # Images and static assets
│   └── dashboard_mockup.png
└── archive/                # Archived documentation
    └── GIT_SETUP_GUIDE.md
```

## ✨ Features

- **Glassmorphism Design**: Modern frosted-glass aesthetic with backdrop blur effects
- **Bento Grid Layout**: Dynamic card-based layout inspired by modern UI trends
- **Animated Mesh Background**: Subtle gradient mesh with fixed attachment
- **Responsive Bento Grid**: Adapts from 1-column (mobile) to 4-column (desktop)
- **Pride Integration**: Rainbow gradient header and authentic LGBTQ+ representation
- **Interactive Hover Effects**: Smooth transforms and shadow transitions on cards
- **Fast Performance**: Single HTML file with CDN resources, instant load times
- **Zero Build Process**: Pure HTML with Tailwind CDN—edit and refresh
- **Font Awesome Icons**: Professional iconography throughout
- **Inter Font Family**: Clean, modern typography via Google Fonts

## 🎯 Bento Grid Sections

- **Hero Card** (2x2): Introduction, tagline, social links, and availability badge
- **Beyond Code Card** (1x1): LGBTQ+ values and community commitment with pride flag header
- **Tech Stack Card** (1x2): Skills organized by category (Engineering, Full Stack, Reporting, Operations)
- **Featured Project Card** (3x2): RetailOps case study with image, metrics, and CTA
- **Executive Dashboard Card** (1x1): Additional project showcase with tech badges
- **Contact CTA Card** (4x1): Full-width call-to-action footer
- **Copyright Footer**: Attribution and pride emoji

## 🌈 LGBT+ Community Integration

This portfolio authentically represents:
- Support for workplace diversity and inclusion
- Commitment to inclusive design practices
- Active advocacy for LGBT+ tech communities
- Pride color integration throughout the design
- Links to organizations: HRC, Lambda Legal, GLSEN

## 🛠️ Customization

### Update Your Information
Edit `index.html` and customize:
- **Name & Title**: Update `<h1>` and `<h2>` in hero card
- **Social Links**: Replace GitHub, LinkedIn, and email URLs in hero section
- **Tagline**: Modify the professional description paragraph
- **Tech Stack**: Update skill badges in the tech stack card (lines ~100-130)
- **Featured Project**: Replace RetailOps content with your project
- **Project Image**: Update `assets/dashboard_mockup.png` path
- **Contact Email**: Update the "Get In Touch" button link

### Add Images
1. Images go in the `assets/` folder
2. Current image: `assets/dashboard_mockup.png` (featured project)
3. Recommended image sizes:
   - Project images: 1200x800px minimum
   - Keep file sizes optimized (< 500KB)

### Customize Colors
The design uses Tailwind CSS classes. Key colors:
- **Primary**: `indigo-500`, `indigo-600` (buttons, accents)
- **Secondary**: `pink-600` (metrics, highlights)
- **Pride Gradient**: `from-red-500 via-yellow-500...to-purple-500`
- **Background Mesh**: Modify `radial-gradient` values in `<style>` section

### Modify Bento Grid Layout
Adjust card sizes by changing Tailwind grid classes:
- `col-span-1` through `col-span-4` (horizontal span)
- `row-span-1` through `row-span-2` (vertical span)
- `md:col-span-X` for tablet breakpoints
- `lg:col-span-X` for desktop breakpoints

## 🚀 Deployment

### GitHub Pages (Current)
- Already deployed to: `https://emailandiee-mje.github.io/portfolio-mje/`
- Automatic deployment on push to `main` branch
- Free hosting with HTTPS
- No build process required

### Alternative Hosting Options
- **Netlify**: Drag-and-drop the `index.html` file
- **Vercel**: Connect GitHub repo for auto-deploy
- **Cloudflare Pages**: GitHub integration with global CDN

## 🎨 Design Philosophy

### Glassmorphism Aesthetic
The design uses modern glassmorphism principles:
- **Frosted Glass Cards**: `backdrop-filter: blur(16px)` with transparency
- **Layered Depth**: Multiple blur levels and shadows create depth
- **Animated Mesh**: Multi-color radial gradients create organic background
- **Hover States**: Cards lift and brighten on hover

### Bento Grid System
Inspired by Apple's design language:
- **Asymmetric Layout**: Cards of varying sizes create visual interest
- **Responsive Flow**: Grid adapts from 1→2→4 columns based on viewport
- **Auto-Rows**: Minimum 180px height with content-based expansion
- **Gap Consistency**: 1.5rem (24px) spacing throughout

### Technical Implementation
- **Tailwind CSS CDN**: No build process, instant styling
- **CSS Custom Properties**: Reusable gradient and blur values
- **Font Awesome 6**: Vector icons loaded via CDN
- **Google Fonts**: Inter font family for crisp readability

## 📈 Potential Enhancements

- [ ] Add more project cards (currently 2 featured)
- [ ] Implement modal overlays for project details
- [ ] Add smooth scroll animations with Intersection Observer
- [ ] Create downloadable resume PDF
- [ ] Add blog section with markdown support
- [ ] Implement dark mode toggle
- [ ] Add case study videos or GIF demos
- [ ] Convert to Next.js for dynamic routing (future)
- [ ] Add contact form with backend integration
- [ ] Implement analytics tracking

## 📊 Current Projects Featured

### RetailOps ERP & Intelligence Engine (Featured)
- **Description**: Full-stack serverless ecosystem with web app, ETL pipeline, and "Time Machine" SQL model
- **Tech Stack**: Tailwind, Apps Script, BigQuery, SQL
- **Impact Metrics**: 100% paperless, daily auto-reporting
- **Highlights**: Historical revenue tracking against inflation, complete workflow automation
- **Link**: GitHub case study (https://github.com/emailandiee-mje/retail-ops-gcp-pipeline)

### Executive Sales Dashboard
- **Description**: Multi-region KPI monitoring system
- **Tech Stack**: Power BI, DAX, SQL
- **Scale**: Handles 5M+ rows
- **Type**: Business intelligence reporting

## ♿ Accessibility Considerations

- Semantic HTML5 structure with proper heading hierarchy
- Alt text on project images
- Sufficient color contrast on all text (verified 4.5:1 ratio)
- Focus indicators on interactive elements
- Hover states for visual feedback
- Icon labels via title attributes
- Responsive font sizes (responsive across devices)

**Note**: Further accessibility testing recommended for full WCAG 2.1 AA compliance

## 🌈 LGBTQ+ Representation

Authentic integration throughout the portfolio:
- **Pride Flag Header**: Rainbow gradient on "Beyond Code" card
- **Inclusive Emojis**: 🏳️‍🌈 🏳️‍⚧️ 🤝 representing community
- **Values Statement**: Clear commitment to diversity and inclusion
- **Footer Attribution**: "Built with Pride" messaging
- **Professional Context**: LGBTQ+ advocacy integrated with technical expertise

## 🔗 Important Links

- **GitHub Repo**: https://github.com/emailandiee-mje/portfolio-mje
- **Project Plan**: See PROJECT_PLAN.md for detailed specifications
- **Accessibility**: https://www.w3.org/WAI/WCAG21/quickref/

## 📞 Support Organizations

Links included in portfolio for:
- **Human Rights Campaign (HRC)**: https://www.hrc.org/
- **Lambda Legal**: https://www.lambdalegal.org/
- **GLSEN**: https://www.glsen.org/
- **Other**: Add more as appropriate

## 📄 License

This portfolio is your personal property. Feel free to customize, share, and evolve it.

## 🎉 Getting Started

1. **View Locally**: Open `index.html` in your browser
2. **Customize**: Update content with your projects and info
3. **Add Assets**: Create `assets/` folder and add images
4. **Push to GitHub**: Follow deployment instructions
5. **Share**: Send link to recruiters, colleagues, and community

---

**Last Updated**: November 30, 2025  
**Status**: Live on GitHub Pages  
**Version**: 2.0 (Glassmorphism Bento Grid Design)  
**Live URL**: https://emailandiee-mje.github.io/portfolio-mje/

Built with ❤️ using Tailwind CSS, glassmorphism, and commitment to inclusive design.
🏳️‍🌈 Proudly supporting LGBTQ+ communities in tech.
