# KK Computers Website

## Overview

This is a static website for KK Computers, an IT training institute that offers comprehensive technology education, certifications, and software development services. The website is built as a multi-page static site using modern web technologies with a focus on responsive design and user experience. All 55 user-provided images have been integrated into the website, including 4 logo variations, team photos, gallery images, course materials, and certification logos.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

The website follows a traditional multi-page static architecture with:

- **Frontend**: Pure HTML5, CSS3, and JavaScript with Tailwind CSS framework
- **Architecture Pattern**: Static multi-page application (MPA)
- **Styling**: Utility-first CSS with Tailwind CSS via CDN
- **JavaScript**: Vanilla JavaScript for interactivity
- **Asset Management**: Static file serving for images, CSS, and JavaScript

## Key Components

### 1. Page Structure
- **index.html**: Homepage with hero section and overview
- **about.html**: Company information and team details
- **services.html**: IT training and certification offerings
- **events.html**: Upcoming events and workshops
- **contact.html**: Contact information and forms

### 2. Navigation System
- Responsive navigation header with mobile hamburger menu
- Consistent navigation across all pages
- Active page highlighting
- Mobile-first responsive design

### 3. Asset Organization
- **assets/css/style.css**: Custom CSS with CSS variables for theming
- **assets/js/main.js**: JavaScript for interactive functionality
- **assets/images/logos/**: Logo files (main-logo.png, header-logo.png, director-logo.png, about-logo.png)
- **assets/images/hero/**: Hero carousel images (hero-1.jpg, hero-2.jpg)
- **assets/images/gallery/**: Gallery images from different locations (darsi-1.jpg to darsi-5.jpg, guntur-1.jpg to guntur-7.jpg, sam-1.jpg to sam-8.jpg)
- **assets/images/team/**: Team member photos (team-1.jpg to team-4.jpg, prasad.jpg, lakshmi.jpg, bhaskhar.jpg, srinu.jpg, surendra.jpg)
- **assets/images/services/**: Service category images (course-1.jpg to course-3.jpg, category-1.jpg to category-4.jpg)
- **assets/images/courses/**: Course-specific images (microsoft.png, tally.png, dtp.png, photoshop.png, etc.)
- **assets/images/certifications/**: Certification logos (ddugky.png, mepma.png, nsdc.png, pmkvy.png, seedap.png, etc.)
- **assets/images/testimonials/**: Student testimonial photos (testimonial-1.jpg to testimonial-4.jpg)

### 4. Interactive Features
- Mobile menu toggle functionality
- Hero carousel with auto-play and manual navigation
- Lightbox for image galleries
- Contact form handling
- FAQ accordion sections
- Scroll animations
- Lazy loading for images

## Data Flow

The website operates as a static site with client-side interactivity:

1. **Page Loading**: Static HTML files served directly
2. **Styling**: Tailwind CSS loaded via CDN + custom CSS
3. **JavaScript**: DOM manipulation for interactive elements
4. **User Interactions**: Handled entirely on the client-side
5. **Forms**: Contact forms (implementation pending backend integration)

## External Dependencies

### CDN Dependencies
- **Tailwind CSS**: `https://cdn.tailwindcss.com` - Utility-first CSS framework
- **Font Awesome**: `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css` - Icon library

### Design System
- **CSS Variables**: Custom properties for consistent theming
- **Color Palette**: Primary blue (#2563eb), secondary purple (#7c3aed), accent yellow (#eab308)
- **Typography**: Inter font family with system font fallbacks
- **Responsive Breakpoints**: Mobile-first approach using Tailwind's responsive utilities

## Deployment Strategy

The website is designed for static hosting and can be deployed to:

- **Static Hosting Platforms**: Netlify, Vercel, GitHub Pages
- **CDN**: Cloudflare, AWS CloudFront
- **Traditional Web Hosting**: Any web server capable of serving static files

### Deployment Requirements
- No server-side processing required
- No database dependencies
- Simple file structure for easy hosting
- CDN dependencies for external resources

### Performance Considerations
- Optimized for fast loading with minimal dependencies
- Lazy loading implementation for images
- Efficient CSS with utility classes
- Vanilla JavaScript for minimal bundle size

### Future Enhancements
- Contact form backend integration
- Content Management System (CMS) integration
- Search functionality
- Blog section
- User authentication for course enrollment
- Payment processing integration