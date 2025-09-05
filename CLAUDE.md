# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a high-converting, standalone landing page for The Strikers Lab's 6-Week Spring Shred Challenge built with Tailwind CSS for optimal maintainability and performance.

## File Structure

```
TSLG/
├── index.html                      # Main landing page with Tailwind CSS (67KB)
├── README.md                       # Project documentation
├── DESIGN_IMPLEMENTATION.md        # UI design specifications and features
├── TAILWIND_SHADCN_IMPLEMENTATION.md # Tailwind/Shadcn implementation details
├── TSLG - Landing Page Copy.pdf   # Original copy document
└── .claude/                       # Claude Code configuration
    └── settings.local.json        # Local permissions
```

## Development Commands

Since this is a static HTML landing page project, no build tools or package managers are required:

- **Local Development**: Open `index.html` directly in browser or use a local server
- **Testing**: Test responsive design at breakpoints: 320px, 768px, 1024px, 1200px
- **Validation**: Validate HTML with W3C validator, check accessibility with browser dev tools

## Architecture & Implementation

### Implementation Approach

**Tailwind CSS Implementation** (`index.html`)
- Uses Tailwind CSS CDN with custom configuration
- Shadcn UI-inspired component patterns  
- Utility-first approach with custom brand colors
- Enhanced animations and interactions
- 67KB optimized for performance and maintainability

### Key Technical Features

- **Mobile-First Responsive**: Breakpoints at 320px, 768px, 1024px, 1200px
- **Performance Optimized**: Critical CSS inlined, lazy loading ready
- **SEO Complete**: Meta tags, Open Graph, Twitter cards, structured data
- **Analytics Ready**: Placeholders for Google Analytics, Facebook Pixel, Hotjar
- **Accessibility**: WCAG 2.1 AA compliant with AAA color contrast
- **Cross-Browser**: Modern browser support with graceful degradation

### Design System

- **Colors**: Black (#000000), Red (#dc2626), White (#ffffff)
- **Typography**: System font stack with responsive clamp() sizing
- **Components**: Enhanced CTA buttons, testimonial cards, FAQ accordion
- **Layout**: 13 distinct sections with alternating backgrounds
- **Interactions**: Hover effects, smooth scrolling, FAQ animations

## Content Management

### Required Updates for Deployment

1. **Replace Placeholders**:
   - Update `GA_MEASUREMENT_ID` with Google Analytics ID
   - Update `FACEBOOK_PIXEL_ID` with Facebook Pixel ID  
   - Update `HOTJAR_ID` with Hotjar tracking ID
   - Replace `href="#booking"` with actual booking system URL

2. **Image Replacements**:
   - Google Reviews screenshot
   - Transformation before/after photos
   - Coach Franz professional photo

### Content Structure

- **13 Sections**: Hero, Problem Agitation, Social Proof, Transformations, Value Proposition, Process Steps, Value Stack, Guarantee, Coach Profile, Comparison Table, Target Audience, FAQ, Final Urgency
- **10+ CTAs**: Strategically placed throughout for conversion optimization
- **Copy Source**: All content matches TSLG - Landing Page Copy.pdf exactly

## Development Guidelines

- **Netlify Deployment**: `index.html` is ready for direct deployment to Netlify
- **Responsive Testing**: Always test on mobile devices first
- **Performance**: Maintain <3 second load time on 3G networks
- **Accessibility**: Preserve WCAG compliance when making changes
- **Analytics**: Test tracking implementation before deployment

## Conversion Optimization Features

- **Scarcity Indicators**: Limited time offers and urgency messaging
- **Social Proof**: Google Reviews integration and testimonials  
- **Risk Reversal**: Money-back guarantee prominent throughout
- **Multiple CTAs**: 10+ strategically placed call-to-action buttons
- **Mobile Optimization**: Thumb-friendly placement and full-width CTAs