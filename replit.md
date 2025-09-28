# Simple Omelette Recipe Page

## Overview

This is a static recipe webpage showcasing a simple omelette recipe. The project features a responsive, well-styled recipe card built using only vanilla HTML and CSS. The page displays recipe information including preparation time, ingredients, instructions, and nutritional information in a clean, modern design that matches the provided Frontend Mentor style guide exactly.

**Project Status**: ✅ Completed - All requirements implemented and tested

## User Preferences

Preferred communication style: Simple, everyday language.

## Recent Changes (September 28, 2025)

- ✅ Built complete static recipe page with vanilla HTML5 and CSS3
- ✅ Implemented responsive design matching provided desktop and mobile mockups
- ✅ Applied proper typography using Google Fonts (Young Serif + Outfit)
- ✅ Integrated exact color scheme from style guide (Stone, Brown, Rose palette)
- ✅ Added semantic HTML structure with proper accessibility features
- ✅ Created nutrition table with semantic markup and screen reader support
- ✅ Set up Python HTTP server workflow for local development
- ✅ Verified cross-device compatibility and layout accuracy

## Project Architecture

### Frontend Structure
- **Static Files**: Pure HTML5/CSS3 implementation (no JavaScript)
- **Entry Point**: `index.html` - Main recipe page
- **Styling**: `style.css` - Complete responsive styling
- **Assets**: `assets/images/` - Recipe photo and favicon
- **Server**: Python HTTP server on port 5000

### Design Implementation
- **Layout**: Centered card design (max-width: 736px) with proper spacing
- **Typography**: Young Serif (headings) + Outfit (body text) from Google Fonts
- **Color System**: HSL-based color palette matching style guide specification
- **Responsive**: Mobile-first design (375px → 1440px+) with proper breakpoints
- **Accessibility**: Semantic HTML5, proper table structure, screen reader support

### Content Structure
1. **Hero Section**: Full-width recipe image with proper border radius
2. **Recipe Title & Description**: Clear hierarchy with Young Serif headings
3. **Preparation Time**: Highlighted section with rose background
4. **Ingredients**: Bulleted list with custom styling
5. **Instructions**: Numbered list with proper semantic markup
6. **Nutrition Table**: Accessible table with row headers and hidden caption

### Technical Features
- **Semantic HTML**: Proper use of sections, headings, lists, and table elements
- **CSS Grid/Flexbox**: Modern layout techniques for responsive design
- **Custom Properties**: HSL color variables for consistent theming
- **Media Queries**: Responsive breakpoints for mobile and desktop
- **Accessibility**: Screen reader support, focus styles, proper contrast
- **Performance**: Optimized images, efficient CSS, minimal HTTP requests

## External Dependencies

### Fonts
- **Google Fonts**: Young Serif (400) + Outfit (400, 600, 700)
- **Loading**: Preconnect optimization for improved performance

### Assets
- **Recipe Image**: High-quality omelette photo with proper alt text
- **Favicon**: 32x32 PNG icon for browser tabs
- **Optimized**: All images properly sized and compressed

### Browser Support
- **Modern Standards**: HTML5, CSS3, Flexbox, Grid support
- **Responsive**: Tested across mobile and desktop viewports
- **Accessibility**: WCAG compliant with semantic markup