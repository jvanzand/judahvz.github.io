# Judah Van Zandt - Research Website

A clean, professional research website built with HTML, CSS, and vanilla JavaScript. This site follows modern web design principles and is fully responsive.

## Site Structure

```
judahvz.github.io/
├── index.html              # Landing page (About Me)
├── research.html           # Research overview and topics
├── publications.html       # Selected publications
├── style.css               # Main stylesheet
├── script.js               # JavaScript functionality
├── images/                 # Image directory
│   └── profile.jpg         # Profile photo (placeholder)
└── README.md              # This file
```

## Pages

### 1. **index.html** - About Me (Landing Page)
- Navigation menu linking to all pages
- Header with your name and title
- Profile image
- About Me section with biography
- Education history section
- Contact and CV links

### 2. **research.html** - Research
- Research overview
- Multiple research topic sections
- Collaborations section
- Flexible layout for expanding research areas

### 3. **publications.html** - Selected Publications
- Links to publication databases (ADS, arXiv, ORCID)
- Individual publication entries with:
  - Title
  - Authors
  - Journal information
  - Abstract/summary
  - Links to arXiv, ADS, and DOI

## Customization Guide

### Adding Your Information

1. **Profile Image**: Replace `images/profile.jpg` with your own photo (250x250px recommended)

2. **Personal Information**:
   - Edit your name in the header sections of all HTML files
   - Update your title/position in `index.html`
   - Add your email in the contact link

3. **About Me Section** (`index.html`):
   - Replace placeholder text with your biography
   - Add education entries

4. **Research Topics** (`research.html`):
   - Add your research areas
   - Describe methods and significance
   - Add collaborators and institutions

5. **Publications** (`publications.html`):
   - Update publication links to your actual ADS/arXiv profiles
   - Add your publications with titles, authors, and abstracts
   - Update arXiv, ADS, and DOI links

### Styling Modifications

The site uses a purple gradient header (`#667eea` to `#764ba2`) and blue accents (`#0066cc`). To change colors:

1. Open `style.css`
2. Update the `background` property in `.header` (line ~70)
3. Update `#0066cc` color values throughout the file

### Adding Links

- **CV**: Update the href in the "CV (PDF)" button
- **Contact**: Update the email address in the contact link
- **External Links**: Use `target="_blank"` for external links

## Technical Details

- **Responsive Design**: Mobile-friendly layout with breakpoints at 768px and 480px
- **No Dependencies**: Pure HTML, CSS, and vanilla JavaScript
- **Performance**: Lightweight, fast-loading pages
- **Accessibility**: Semantic HTML structure

## Deployment

This site is designed to be deployed on GitHub Pages:

1. Push all files to your `judahvz.github.io` repository
2. GitHub automatically serves it at `https://judahvz.github.io`
3. No build process needed

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## File Placeholders to Update

Replace the following placeholders with actual content:

| Placeholder | Location | What to Replace |
|-------------|----------|-----------------|
| `[Your Title/Position]` | index.html | Your current position |
| `[Insert your biography...]` | index.html | Your biography |
| `[Degree Type, Field...]` | index.html | Your education entries |
| `images/profile.jpg` | All pages | Your profile photo |
| `your.email@example.com` | All pages | Your email address |
| `[Research Topic X]` | research.html | Your research areas |
| `[Publication Title X]` | publications.html | Your publications |
| `#` links in publications | publications.html | Actual arXiv/ADS/DOI links |

## Navigation

The site includes a sticky navigation bar with links to:
- About Me (index.html)
- Research (research.html)
- Selected Publications (publications.html)

The active page is automatically highlighted based on the current URL.

## Footer

The footer automatically displays the current year and includes copyright information. The year updates automatically each January 1st.

## Features

✓ Responsive design (mobile, tablet, desktop)
✓ Sticky navigation menu
✓ Smooth scrolling
✓ Professional styling
✓ Placeholder structure for easy customization
✓ No external dependencies
✓ Fast loading
✓ Print-friendly layout

## Notes

- All placeholder images should be placed in the `images/` folder
- PDF files (CV) can be stored in the root directory or a separate folder
- Consider adding a `.gitignore` file if storing sensitive information

## License

Feel free to customize this template as needed for your research website.
