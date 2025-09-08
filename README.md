# Upstate Home Remodel Website

A modern, responsive website for Upstate Home Remodel, built with Astro and featuring professional home improvement services throughout Upstate South Carolina.

## 🏠 About

**Upstate Home Remodel** is owned and operated by **Jeffery Lincoln**, a licensed and insured contractor specializing in:

- **Carpentry & Custom Woodwork** - Custom cabinets, built-ins, trim work, and finish carpentry
- **Kitchen & Bathroom Renovations** - Complete remodels and updates
- **Electrical Services** - Panel upgrades, lighting, and code compliance
- **Plumbing Services** - Repairs, installations, and emergency services
- **General Home Improvement** - Flooring, painting, decks, and complete renovations

### Service Areas
- Greenville County
- Spartanburg County  
- Anderson County
- Pickens County
- Oconee County
- Surrounding Areas

**Contact:** (864) 608-3326 | Available 7 days a week with 24/7 emergency service

## 🚀 Tech Stack

- **Framework:** [Astro](https://astro.build) - Static Site Generator
- **Styling:** Custom CSS with CSS Variables
- **Icons:** Material Icons
- **Animations:** GSAP with ScrollTrigger
- **Typography:** Source Serif 4 Display & Proxima Nova
- **Build Tool:** Vite (included with Astro)
- **Type Checking:** TypeScript

## 📁 Project Structure

```
/
├── public/
│   ├── images/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Navigation.astro
│   │   ├── HeroDefault.astro
│   │   ├── TestimonialCard.astro
│   │   ├── CtaSection.astro
│   │   ├── Footer.astro
│   │   └── ...
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── about.astro
│   │   ├── services.astro
│   │   ├── gallery.astro
│   │   ├── reviews.astro
│   │   └── contact.astro
│   └── styles/
│       └── global.css
└── package.json
```

## 🎨 Design System

### Colors
- **Primary Brown:** #664733
- **Secondary Brown:** #806640  
- **Accent Gold:** #E6A12E
- **Hover Gold:** #D4941A
- **Text Primary:** #262626
- **Text Light:** #664733
- **Light Gray:** #F8F9FA
- **White:** #FFFFFF

### Typography
- **Headings:** Source Serif 4 Display
- **Body Text:** Proxima Nova

### Spacing
- Uses CSS custom properties for consistent spacing
- Button padding optimized for accessibility
- Responsive container with max-width: 1400px

## 🛠️ Development

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation
```bash
npm install
```

### Development Server
```bash
npm run dev
# or
npm start
```

### Build for Production
```bash
npm run build
```

### Preview Production Build
```bash
npm run preview
```

## 🔧 Custom Commands

### /sync-wp-astro
Synchronizes WordPress content with Astro static site by:
1. Fetching latest content from WordPress REST API
2. Rebuilding Astro static files
3. Triggering Netlify deployment if needed

**Usage:** Run when WordPress content has been updated

### /sync-code  
Synchronizes ALL code between WordPress theme and Astro frontend by:
1. Reading all WordPress theme files (header.php, footer.php, style.css, functions.php)
2. Analyzing HTML structure, CSS classes, and JavaScript functionality
3. Creating exact 1:1 sync of WordPress code to Astro BaseLayout
4. Maintaining identical mobile menu, header scroll effects, and responsive behavior
5. Preserving all class names (site-logo-image, mobile-menu-close, nav-link)
6. Matching JavaScript event handling (window.pageYOffset, position: fixed scroll lock)
7. Porting all CSS styles including responsive breakpoints and WordPress-specific styling
8. Testing and rebuilding Astro with synchronized code
9. Updating project documentation with sync status

**Usage:** Run when WordPress theme code has been modified and needs to be exactly replicated in Astro frontend

## 📱 Features

- **Responsive Design** - Mobile-first approach with breakpoints at 768px and 480px
- **SEO Optimized** - Semantic HTML, meta tags, and structured data
- **Accessibility** - ARIA labels, focus states, and keyboard navigation
- **Performance** - Static site generation, optimized images, and minimal JavaScript
- **Animation** - GSAP-powered scroll animations and micro-interactions
- **Modern UI** - Clean design with hover effects and smooth transitions

### Key Components

- **HeroDefault** - Standardized hero sections across all pages
- **TestimonialCard** - Customer review cards with ratings and profile images
- **CtaSection** - Call-to-action sections with gradient backgrounds
- **Navigation** - Responsive navigation with mobile menu
- **ServiceAreas** - Interactive service area display

## 📊 Performance

- **Static Site Generation** - Pre-rendered pages for optimal performance
- **Minimal JavaScript** - Only essential JavaScript for interactions
- **Optimized CSS** - Custom CSS with CSS variables, no external frameworks
- **SEO Ready** - Proper meta tags, structured data, and semantic HTML

## 🚢 Deployment

The site is configured for deployment on Netlify with automatic builds from the main branch.

### Build Command
```bash
npm run build
```

### Publish Directory
```
dist/
```

## 📞 Contact Information

**Jeffery Lincoln**  
Upstate Home Remodel  
Phone: (864) 608-3326  
Email: info@lincolnlogshms.com  
Available 7 days a week, emergency service 24/7

## 🎨 About CT Web Design Shop

**Website Developer:** Clifton T Canady  
**Company:** CT Web Design Shop  
**Website:** https://ctwebdesignshop.com/

CT Web Design Shop specializes in creating modern, responsive websites for small businesses and contractors. This Upstate Home Remodel website showcases custom web development using cutting-edge technologies like Astro, focusing on performance, SEO, and user experience.

### Services Offered:
- Custom Website Development
- WordPress to Static Site Migration
- E-commerce Solutions
- SEO Optimization
- Responsive Design
- Performance Optimization

---

Built with ❤️ using Astro for fast, modern web performance.