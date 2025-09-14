# tongkyu.kim.github.io
Professional CV website for Tongkyu Kim - Interdisciplinary climate researcher specializing in climate governance and environmental behavior.

## Overview

This is a comprehensive academic CV website featuring:
- **Professional Profile**: Current position at Korea Development Institute (KDI)
- **Education & Training**: M.A. in Environmental Policy, certifications from Cambridge and KNDA
- **Experience**: Government, multilateral, and academic research positions
- **Publications**: Peer-reviewed articles, policy papers, and working papers
- **Projects**: Government, bilateral/multilateral, and corporate collaborations
- **Public Outreach**: Speaking engagements and international conferences

## Features

- **Responsive Design**: Optimized for desktop and mobile viewing
- **Interactive Icons**: Four-type icon system with hover effects
  - 🌐 Web icons (blue) - External links to organizations/projects
  - 📄 DOI icons (blue) - Direct links to published papers
  - 📝 Review icons (blue) - Links to preprint versions under review
  - 📰 News icons (green) - Links to news articles about research
  - 💬 Popup icons (gray) - Additional context and details
- **Professional Typography**: Museo Sans font family for clean, academic appearance
- **Smooth Navigation**: Sticky navbar with smooth scrolling and active section highlighting
- **Social Media Integration**: Links to Google Scholar, ORCID, LinkedIn, and GitHub

## Local Development

Start the local development server:
```bash
npm start
# or
python3 -m http.server 8000
```

Then open your browser to: http://localhost:8000

## File Structure

```
/
├── index.html              # Main website file with complete CV content
├── src/
│   ├── css/
│   │   └── popup.css      # Icon styling and popup functionality
│   ├── js/
│   │   └── popup.js       # Interactive popup scripts
│   ├── icons/             # Social media and UI icons
│   ├── images/
│   │   └── profile.JPG    # Professional profile photo
│   └── pdfs/              # Research papers and documents
├── package.json           # NPM configuration
├── README.md             # This file
├── CNAME                 # Custom domain configuration
└── .gitignore           # Git ignore rules
```

## Development Commands

- `npm start` or `npm run serve` - Start local development server
- `npm run dev` - Start development server (same as above)
- `npm run build` - No build step needed for static site
- `npm run deploy` - Reminder about GitHub Pages deployment

## Content Highlights

### Recent Updates (September 2025)
- **Icon System Simplification**: Streamlined from 6 to 4 icon types for better UX
- **News Integration**: Added green news icons linking to media coverage of research
- **Enhanced Publications**: 8 peer-reviewed articles with proper academic formatting
- **Project Portfolio**: 11 major projects spanning government, multilateral, and corporate sectors
- **Public Engagement**: 9 speaking engagements and 4 major conference organizations

### Key Research Areas
- Climate governance and Article 6 mechanisms
- Voluntary carbon market integrity
- Environmental behavior and behavioral rebounds
- Transboundary environmental policies
- Circular economy and sustainability strategies

## Deployment

This website automatically deploys to GitHub Pages when you push to the main branch at:
https://tongkyu-kim.github.io/tongkyu.kim.github.io

## Technical Details

- **CSS Framework**: Custom responsive design with CSS Grid and Flexbox
- **JavaScript**: Vanilla JS for interactive features and smooth navigation
- **Color Scheme**: Professional navy and green accent colors
- **Performance**: Optimized images and minimal dependencies for fast loading
- **Accessibility**: Semantic HTML and proper ARIA labels for screen readers

## Customization

The website is built with modular sections that can be easily updated:

1. **Profile Section**: Update personal information and social links
2. **Experience Section**: Add new positions or modify existing ones
3. **Publications Section**: Update with new papers and research outputs
4. **Projects Section**: Add new collaborations and funding information
5. **Outreach Section**: Include speaking engagements and media appearances

### Icon System Usage
```html
<!-- Web link to organization -->
<a href="https://example.org" target="_blank"><span class="web-icon"></span></a>

<!-- DOI link to published paper -->
<a href="https://doi.org/10.1016/..." target="_blank"><span class="doi-icon"></span></a>

<!-- Preprint link for paper under review -->
<a href="https://papers.ssrn.com/..." target="_blank"><span class="rev-icon"></span></a>

<!-- News article link -->
<a href="https://news-site.com/..." target="_blank"><span class="news-icon"></span></a>

<!-- Popup with additional context -->
<span class="popup-icon" data-popup-type="custom-content"></span>
```

## Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## License

© 2025 by Tongkyu Kim. All rights reserved.
