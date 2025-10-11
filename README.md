# Capstone Project 2 - Personal Website with CSS & Bootstrap

## What I Have Done in This Project

This project is a comprehensive personal website that evolved from a basic HTML-only site (Capstone 1) to a fully-styled, responsive website with CSS and Bootstrap integration (Capstone 2). Here's what I accomplished:

### Core Development:

- **Built 5+ interconnected web pages** with consistent navigation and design
- **Implemented 3 different CSS layout techniques** on the same gallery content:
  - Float + Position layout (`gallery-float.html`)
  - Flexbox layout (`gallery-flexbox.html`)
  - CSS Grid layout (`gallery-grid.html`)
- **Created a unified external stylesheet** (`style.css`) with professional styling
- **Integrated Bootstrap framework** for a modern contact form with responsive components
- **Added interactive layout switcher** allowing users to compare different CSS approaches side-by-side

### Technical Features:

- Responsive design that works on all devices (mobile-first approach)
- Professional styling with hover effects, gradients, and smooth transitions
- Accessible forms with proper labels and validation states
- Real project portfolio with live links to deployed applications
- Cross-browser compatibility and performance optimization

## What I Learned While Doing It

This project was an intensive learning experience in modern web development:

### CSS Mastery:

- **Layout Techniques**: Gained hands-on experience with Float, Flexbox, and CSS Grid by implementing the same gallery using all three methods
- **Responsive Design**: Learned to create layouts that adapt seamlessly across devices using media queries and flexible units
- **Advanced Styling**: Mastered CSS gradients, shadows, transforms, transitions, and pseudo-classes/elements
- **CSS Architecture**: Understood the importance of organized, maintainable CSS with proper naming conventions

### Bootstrap Framework:

- **Component-Based Development**: Learned to leverage pre-built Bootstrap components for rapid development
- **Grid System**: Mastered Bootstrap's 12-column responsive grid system
- **Utility Classes**: Discovered the power of utility-first CSS for quick styling
- **Framework Integration**: Learned to combine custom CSS with Bootstrap while maintaining design consistency

### Development Best Practices:

- **Mobile-First Approach**: Started with mobile design and enhanced for larger screens
- **Progressive Enhancement**: Built solid HTML foundation, then enhanced with CSS
- **Accessibility**: Implemented proper semantic HTML, form labels, and keyboard navigation
- **Performance Optimization**: Wrote efficient CSS selectors and minimized HTTP requests

### Comparative Analysis:

Through building the same gallery with different layout methods, I learned:

- **Float**: Traditional but requires clearfix and careful positioning
- **Flexbox**: Perfect for one-dimensional layouts and flexible content
- **Grid**: Ideal for two-dimensional layouts and complex arrangements

## What the Purpose of This Website Is

This website serves multiple important purposes:

### 1. **Academic Portfolio & Learning Documentation**

- Demonstrates web development skills learned in the Web & Mobile Development course
- Shows progression from basic HTML to advanced CSS and Bootstrap integration
- Provides practical examples of different layout techniques for educational reference

### 2. **Professional Portfolio & Personal Branding**

- Showcases real projects and technical experience from internships and startup work
- Highlights leadership roles in tech community (USG Future Hub, Software Engineering Club)
- Establishes professional online presence for networking and career opportunities

### 3. **Practical Learning Laboratory**

- Serves as a testing ground for new web technologies and techniques
- Allows experimentation with different CSS approaches and frameworks
- Provides real-world experience in responsive design and modern development practices

### 4. **Career Development Tool**

- Acts as a living resume with detailed project descriptions and live links
- Demonstrates both technical skills and professional experience to potential employers
- Shows ability to build complete, production-ready web applications

The website represents not just coursework completion, but a comprehensive demonstration of modern web development skills applicable to real-world projects and professional environments.

---

## Overview

This is a comprehensive multi-page personal website built as part of the Web & Mobile Development course capstone project. The website demonstrates proficiency in HTML structure, CSS styling, responsive design, layout techniques (Float+Position, Flexbox, Grid), and Bootstrap framework integration.

## Project Structure

```
├── index.html                    # Home page with personal introduction
├── education-and-experience.html # Education history and professional experience
├── schedule.html                 # Weekly class schedule table
├── contact.html                  # Contact form with custom CSS styling
├── contact-bootstrap.html        # Contact form redesigned with Bootstrap
├── gallery.html                  # Photo gallery with responsive design (Default)
├── gallery-float.html            # Gallery using Float + Position layout
├── gallery-flexbox.html          # Gallery using Flexbox layout
├── gallery-grid.html             # Gallery using CSS Grid layout
├── style.css                     # Unified external stylesheet
├── favicon.ico                   # Website favicon
├── images/
│   ├── profile.png              # Profile picture (now circular with hover effects)
│   └── projects/                # Project showcase images
│       ├── aventra.png
│       ├── crable.png
│       ├── glorri-pricing.png
│       ├── glorri-talents.png
│       ├── ltc-angels.png
│       ├── openconnect.png
│       ├── seclub.png
│       ├── skilltap.png
│       └── usg-website.png
└── README.md                    # Project documentation
```

## Features Implemented

### ✅ Capstone Project 1 Features (HTML Foundation)

- **5+ Pages**: Home, Education & Experience, Schedule, Contact, Gallery
- **Navigation**: Sticky navigation bar with hover effects and active page indicators
- **HTML Content**: Headings, paragraphs, lists, links, images
- **Meta Elements**: Charset, description, author, viewport
- **Tables**: Education history, professional experience, and class schedule with CSS styling
- **Forms**: Comprehensive contact form with multiple input types and CSS styling
- **Favicon**: Included in all pages
- **UTF-8 Encoding**: With emoji usage throughout

### ✅ Capstone Project 2 Features (CSS & Layouts)

#### Part 1: CSS Styling

- **Unified External Stylesheet**: `style.css` connected to all pages
- **Consistent Design**: Same background, fonts (Google Font: Inter), and 90% body width across all pages
- **Enhanced Horizontal Rules**: Shorter, thicker, centered with gradient styling
- **Profile Picture Styling**: Circular (200px × 200px) with hover growth effect (220px × 220px)
- **CSS Table Styling**: Professional table design with hover effects and gradients
- **CSS List Styling**: Enhanced bullet points and numbering with custom colors
- **CSS Form Styling**: Modern form inputs with focus states and validation styling
- **Pseudo-classes & Pseudo-elements**: `:hover`, `:focus`, `:valid`, `:invalid`, `::before`, `::after`

#### Part 2: CSS Layouts (Multiple Techniques)

- **Gallery Layout Variations**: Multiple layout implementations for the same content
  - **Float + Position Layout**: `gallery-float.html` with floating gallery items and positioned elements
  - **Flexbox Layout**: `gallery-flexbox.html` with flexible containers and responsive design
  - **CSS Grid Layout**: `gallery-grid.html` with CSS Grid for automatic responsive columns
- **Layout Switcher**: Interactive navigation between different layout implementations
- **Responsive Design**: All layouts adapt to different screen sizes with appropriate breakpoints

#### Part 3: Unified Navigation

- **Sticky Navigation Bar**: Remains at top when scrolling
- **Hover Effects**: Link styling changes on hover
- **Active Page Indicator**: Different styling for current page link

#### Part 4: Gallery & Responsiveness

- **Photo Gallery Page**: Showcasing all projects with descriptions and live links
- **Multiple Layout Implementations**: Same gallery content displayed using different CSS techniques:
  - **Default Gallery**: Uses existing CSS Grid from main stylesheet
  - **Float Layout**: Traditional float-based positioning with clearfix
  - **Flexbox Layout**: Modern flexible box layout with responsive wrapping
  - **Grid Layout**: CSS Grid with automatic column fitting
- **Layout Comparison**: Interactive switcher to compare different layout approaches
- **Responsive Design**:
  - Desktop: 3 images per row (Float/Flexbox) or auto-fit columns (Grid)
  - Mobile: 1 image per row with stacked layout
- **Media Queries**: Comprehensive responsive breakpoints for all layout types

#### Part 5: Bootstrap Integration

- **Bootstrap Contact Page**: `contact-bootstrap.html` with Bootstrap 5.3.2
- **Bootstrap Components Used**:
  - Responsive navbar with hamburger menu
  - Card components for information sections
  - Grid system (rows and columns)
  - Form components with floating labels
  - Button components with custom gradients
  - Alert and badge components
  - Utility classes for spacing and alignment
- **Bootstrap vs Custom CSS Comparison**: Detailed analysis of pros and cons

### ✅ Additional Enhancements

- **Google Fonts Integration**: Professional Inter font family
- **Advanced CSS Features**: Gradients, shadows, transforms, transitions
- **Accessibility Features**: Proper form labels, ARIA attributes, semantic HTML
- **Performance Optimized**: Efficient CSS selectors and minimal HTTP requests
- **Cross-browser Compatibility**: Works across all modern browsers

## Technical Specifications

### Technical Implementation

#### HTML Elements Used

- Structural: `html`, `head`, `body`, `header`, `nav`, `main`, `section`, `article`, `footer`
- Content: `h1-h4`, `p`, `ul`, `ol`, `li`, `table`, `thead`, `tbody`, `tr`, `th`, `td`
- Media: `img` with proper alt attributes and CSS classes
- Forms: `form`, `fieldset`, `legend`, `label`, `input`, `textarea`, `select`, `option`
- Links: `a` tags for navigation and external links

#### CSS Features Used

- **Selectors**: Element, class, ID, pseudo-class, pseudo-element, attribute selectors
- **Layout**: Float, Position, Flexbox, Grid
- **Styling**: Colors, fonts, spacing, borders, shadows, gradients
- **Responsive**: Media queries, flexible units (%, vh, vw)
- **Animations**: Transitions and transforms for interactive elements

#### Form Input Types

- `text`, `email`, `tel`, `textarea`, `select`, `checkbox`, `radio`, `range`, `submit`, `reset`

#### Layout Techniques Demonstrated

1. **Float + Position**: Traditional layout with floating gallery items (30% width, 3 columns) and clearfix for proper flow
2. **Flexbox**: Modern one-dimensional layout with `flex-wrap` and responsive `flex-basis` calculations
3. **CSS Grid**: Two-dimensional layout system with `repeat(auto-fit, minmax())` for automatic responsive columns

Each technique demonstrates the same gallery content but with different CSS approaches, allowing for direct comparison of layout methods and their responsive behaviors.

#### Accessibility Features

- Proper form labels associated with inputs
- Fieldsets with legends for form organization
- Alt text for all images
- Semantic HTML structure
- Descriptive link text
- Focus indicators and keyboard navigation
- Color contrast compliance

## Live Website

**Portfolio**: [Valeh Ismayilov Personal Website](https://www.valehismayilov.com)
**LinkedIn**: [linkedin.com/in/vismayilov](https://linkedin.com/in/vismayilov)

## What I Learned During This Project

### CSS Mastery

- **Layout Techniques**: Gained deep understanding of Float, Flexbox, and Grid through practical implementation on the same content
- **Comparative Learning**: Built identical gallery layouts using different CSS approaches to understand each method's strengths:
  - **Float**: Learned traditional web layout methods and the importance of clearfix
  - **Flexbox**: Mastered flexible containers and responsive design patterns
  - **Grid**: Understood modern two-dimensional layout capabilities
- **Responsive Design**: Learned to create truly responsive layouts that work across all devices
- **Advanced Styling**: Mastered gradients, shadows, transforms, and animations for modern web aesthetics
- **CSS Architecture**: Understood the importance of organized, maintainable CSS code

### Bootstrap Framework

- **Component-Based Development**: Learned to leverage pre-built components for rapid development
- **Grid System**: Understood Bootstrap's 12-column responsive grid system
- **Utility Classes**: Discovered the power of utility-first CSS for quick styling
- **Customization**: Learned to override Bootstrap defaults while maintaining framework benefits

### Design Principles

- **User Experience**: Focused on intuitive navigation and clear visual hierarchy
- **Accessibility**: Implemented proper form labels, focus states, and semantic structure
- **Performance**: Optimized CSS for faster loading and better user experience
- **Cross-browser Compatibility**: Ensured consistent experience across different browsers

### Development Workflow

- **Mobile-First Approach**: Started with mobile design and enhanced for larger screens
- **Progressive Enhancement**: Built solid HTML foundation, then enhanced with CSS
- **Version Control**: Managed different layout versions and iterations effectively
- **Testing & Debugging**: Developed skills in browser dev tools for CSS debugging

## Purpose of This Website

This website serves multiple purposes:

1. **Academic Portfolio**: Demonstrates web development skills learned in the Web & Mobile Development course
2. **Professional Showcase**: Highlights real projects, experience, and technical capabilities
3. **Learning Documentation**: Shows progression from basic HTML to advanced CSS and Bootstrap
4. **Personal Branding**: Establishes online presence for networking and career opportunities
5. **Practical Application**: Provides real-world experience in responsive web design and modern development practices

The website represents not just coursework completion, but a comprehensive demonstration of modern web development skills applicable to real-world projects and professional environments.

## Setup Instructions

1. **Clone/Download**: Get all HTML and CSS files in the same directory
2. **Dependencies**: External stylesheets (Google Fonts, Bootstrap) are loaded via CDN
3. **Images**: Profile picture and project images are included in `/images/` directory
4. **Formspree Integration**: Contact form uses Formspree for email handling
5. **Content**: All content is customized with real professional information
6. **Browser Compatibility**: Works in all modern browsers (Chrome, Firefox, Safari, Edge)

## Assets Included

- `images/profile.png` - Professional profile picture
- `images/projects/` - Project showcase images for all major projects
- `favicon.ico` - Website favicon

## Browser Compatibility & Performance

- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **Responsive Design**: Works on all screen sizes from mobile to desktop
- **Performance Optimized**:
  - Efficient CSS selectors
  - Minimal HTTP requests
  - Optimized images
  - CSS-only animations
- **Progressive Enhancement**: Graceful degradation for older browsers
- **Accessibility Compliant**: WCAG 2.1 guidelines followed

## Development Insights

### Bootstrap vs Custom CSS Analysis

**What Bootstrap Made Easier:**

- Rapid prototyping with pre-built components
- Consistent responsive grid system
- Professional styling out of the box
- Form validation and interactive elements
- Mobile-first responsive design patterns

**What Was Harder/More Restrictive:**

- Learning framework-specific class naming conventions
- Larger file size and external dependencies
- Less creative freedom for unique designs
- Difficulty customizing beyond default themes
- HTML becomes more verbose with utility classes

**Conclusion:** Bootstrap excels for rapid development and consistency, while custom CSS provides unlimited creative control and performance optimization. The ideal approach often combines both - using Bootstrap for structure and custom CSS for unique branding.

## Project Highlights

- **Real Professional Data**: All experience and education information sourced from LinkedIn
- **Live Project Links**: Working links to actual deployed projects (Skilltap, Glorri, OpenConnect, etc.)
- **Comprehensive Portfolio**: Showcases full-stack development experience across multiple startups
- **Leadership Experience**: Detailed volunteering and leadership roles in tech community
- **Accurate Schedule**: Real Fall 2025 class schedule integrated from calendar data

## Author

Valeh Ismayilov 15706  
3rd Year IT Student  
ADA University

---

## Deployment & Next Steps

### GitHub Repository

This project is version-controlled using Git and hosted on GitHub, maintaining the complete development history from Capstone 1 (HTML-only) through Capstone 2 (CSS + Bootstrap integration).

### Live Website

The website is deployed using GitHub Pages and is accessible at:
**https://vlhsmylv.github.io/web-1-capstone-1/** - _To be updated after deployment_

### Development Process

1. ✅ **Capstone 1**: Built HTML foundation with semantic structure
2. ✅ **Capstone 2**: Added CSS styling, responsive design, and Bootstrap integration
3. ✅ **Layout Variations**: Implemented Float, Flexbox, and Grid versions of gallery
4. ✅ **Documentation**: Created comprehensive README with learning outcomes
5. 🔄 **Deployment**: Push to GitHub and deploy via GitHub Pages
6. 🔄 **Feedback & Iteration**: Share with peers and implement improvements

### Future Enhancements

- Add JavaScript interactivity and animations
- Implement dark/light theme toggle
- Add blog section for technical articles
- Integrate contact form backend functionality
- Optimize for better SEO and performance metrics

This project demonstrates continuous learning and improvement in web development, serving as both an academic achievement and a professional portfolio piece.
