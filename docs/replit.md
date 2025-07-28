# Shahbaz Khan - Personal Portfolio

## Overview

This is a single-page personal portfolio website for Shahbaz Khan, a Technical SEO Specialist & Web Developer from Montréal, QC. The site is built using pure HTML, CSS, and vanilla JavaScript with no frameworks or backend dependencies. It features a dark-themed design inspired by GitHub's aesthetic, with clean UI and animated interactions optimized for quick scanning and user engagement.

## User Preferences

Preferred communication style: Simple, everyday language.
Design preference: Purple-themed UI matching Replit branding, with subtle animated backgrounds and professional appearance.

## System Architecture

### Frontend Architecture
- **Pure Static Site**: Single HTML file with accompanying CSS and JavaScript files
- **No Framework Dependencies**: Built entirely with vanilla HTML5, CSS3, and ES6+ JavaScript
- **Responsive Design**: Mobile-first approach with CSS Grid and Flexbox layouts
- **Progressive Enhancement**: Core functionality works without JavaScript, enhanced features added via JS

### Theme System
- **Dual Theme Support**: Dark theme (default) and light theme toggle
- **CSS Custom Properties**: Centralized color and spacing variables for easy theme switching
- **System Preference Detection**: Respects user's OS theme preference on initial load

## Key Components

### 1. Navigation System
- **Sticky Navigation**: Fixed header with scroll progress indicator
- **Smooth Scrolling**: Anchor-based navigation with offset compensation
- **Mobile Menu**: Hamburger menu for mobile devices
- **Active Link Highlighting**: Visual feedback for current section

### 2. Interactive Elements
- **Scroll Animations**: Fade-in effects triggered by viewport intersection
- **Hover Effects**: Subtle card animations on interactive elements

### 3. Content Sections
- **Minimal Hero Header**: Clean, professional hero section without animations
- **Professional Summary**: Resume overview with scroll-triggered animations
- **Skills Grid**: Categorized skill display with icon-based cards
- **Project Showcase**: Interactive cards for 6 featured projects with external links
- **Experience Timeline**: Professional background display
- **Education Section**: Academic credentials

### 4. Visual Enhancements
- **Clean Design**: Minimal shadows and subtle borders
- **Professional Colors**: GitHub-inspired dark theme with blue accents
- **Smooth Transitions**: Subtle hover effects and animations
- **Typography**: Clean, readable Inter font family

## Data Flow

### State Management
- **Theme State**: Stored in localStorage, applied via CSS class toggle
- **Navigation State**: Active section tracked via scroll position
- **Animation State**: Intersection Observer API for scroll-triggered animations
- **Mobile Menu State**: JavaScript toggle for responsive navigation

### Event Handling
- **Scroll Events**: Throttled scroll listeners for performance
- **Intersection Observer**: Efficient viewport detection for animations
- **Resize Events**: Responsive behavior adjustments
- **Click Events**: Navigation, theme toggle, and external link handling

## External Dependencies

### Fonts
- **Google Fonts**: Inter font family (weights 300-700)
- **Font Awesome**: Icon library for UI elements and social links

### No Backend Dependencies
- **Static Hosting Ready**: Can be deployed to any static hosting service
- **No Database**: All content is hardcoded in HTML
- **No Server-side Processing**: Pure client-side functionality

## Deployment Strategy

### Static Site Deployment
- **GitHub Pages Compatible**: Ready for GitHub Pages deployment
- **CDN Friendly**: Optimized for content delivery networks
- **Caching Strategy**: Long cache times for assets, short for HTML

### Performance Optimizations
- **Preconnect Headers**: DNS prefetching for external resources
- **Font Display Optimization**: Font loading strategies for better performance
- **Image Optimization**: Placeholder system for project screenshots
- **Lazy Loading**: Deferred loading of non-critical resources

### Browser Compatibility
- **Modern Browser Target**: ES6+ features require current browsers
- **Progressive Enhancement**: Graceful degradation for older browsers
- **CSS Grid/Flexbox**: Modern layout techniques with fallbacks

### Recent Changes (July 28, 2025)

### Design Improvements
- **Header Island Design**: Implemented 80% width island-style navigation bar with rounded corners and gap on top
- **Navigation Branding**: Changed logo from "SK" to full name "Shahbaz Khan" in header
- **Hero Section**: Removed island styling from hero, keeping clean simple layout with profile image
- **Purple Theme Implementation**: Changed all accent colors to Replit purple (#8b5cf6)
- **Animated Background**: Added subtle purple gradient background with slow floating animation
- **Light Mode Readability**: Improved font colors in light theme for better contrast and readability
- **Project Screenshots**: Replaced icon placeholders with website placeholder images
- **Contact Section**: Added comprehensive contact form and information display
- **Footer with Social Links**: Added footer with LinkedIn and Instagram social media links
- **Mobile Responsive**: Optimized header island and all sections for mobile devices

## File Structure
```
/
├── index.html          # Main HTML file - clean, minimal structure
├── styles.css          # Minimal professional styling with dark theme
├── script.js           # Simplified JavaScript without cursor/animation overhead
└── attached_assets/    # Project requirements and specifications
```

The architecture now prioritizes professional appearance, minimal design, and clean user experience while maintaining all core functionality.