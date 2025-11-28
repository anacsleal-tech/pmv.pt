# Copilot Instructions for PMV Website

This repository contains the static website for PMV Portugal, a fashion sourcing and facilitation company.

## Project Overview

- **Type**: Static website (HTML, CSS, assets)
- **Languages**: Portuguese (index.html) and English (index-en.html)
- **Styling**: Custom CSS using CSS variables for theming

## Project Structure

```
/
├── index.html          # Main page (Portuguese)
├── index-en.html       # English version
├── css/
│   └── style.css       # Main stylesheet with CSS variables
└── assets/
    └── pmv-logo.png    # Company logo
```

## Code Style Guidelines

### HTML
- Use semantic HTML5 elements (`<header>`, `<main>`, `<section>`, `<footer>`)
- Always include proper `lang` attribute on the `<html>` element
- Include appropriate meta tags for SEO and viewport
- Use the `.container` class for content width control
- Use the `.section` class for page sections

### CSS
- Use CSS custom properties (variables) defined in `:root` for colors and spacing
- Follow the existing naming convention with `--pmv-` prefix for variables
- Maintain responsive design with mobile-first approach
- Use existing utility classes when available

### Key CSS Variables

#### Colors
- `--pmv-primary`: Main brand color (#b45309 - warm brown/orange)
- `--pmv-primary-dark`: Darker variant (#92400e)
- `--pmv-primary-light`: Lighter variant (#d97706)
- `--pmv-secondary`: Secondary color (#1e3a5f - navy blue)
- `--pmv-dark`: Dark text/background (#1f2937)
- `--pmv-light`: Light background (#f9fafb)
- `--pmv-cream`: Warm background accent (#fef7ed)
- `--pmv-text`: Default text color (#374151)
- `--pmv-text-muted`: Muted text (#6b7280)
- `--pmv-border`: Border color (#e5e7eb)
- `--pmv-white`: White (#ffffff)

#### Effects & Sizing
- `--pmv-gradient`: Brand gradient for accents
- `--pmv-shadow`: Standard box shadow
- `--pmv-shadow-lg`: Large box shadow
- `--pmv-radius`: Border radius (0.75rem)
- `--pmv-transition`: Standard transition (all 0.3s ease)

## Bilingual Content

When adding or modifying content:
- Update both `index.html` (Portuguese) and `index-en.html` (English)
- Ensure consistent structure between language versions
- Maintain proper language attributes (`lang="pt"` and `lang="en"`)

## Best Practices

1. **Do not break responsive design** - Test changes at different viewport sizes
2. **Keep both language versions in sync** - Any structural changes should apply to both files
3. **Use existing CSS classes** - Leverage the established design system
4. **Maintain accessibility** - Use proper heading hierarchy, alt text for images, and semantic markup
5. **Preserve SEO elements** - Keep meta descriptions and titles relevant and accurate

## Testing

Since this is a static website:
- Open HTML files directly in a browser to test changes
- Test responsiveness using browser developer tools
- Validate HTML using W3C validator if making structural changes

## Boundaries

- Do not add JavaScript frameworks or build tools unless explicitly requested
- Do not modify the logo or brand assets without approval
- Do not change contact information without verification
