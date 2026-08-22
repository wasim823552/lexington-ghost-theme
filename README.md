# Lexington - Premium Ghost Theme v2.0

<p align="center">
  <strong>SEO-Optimized, Fully Responsive, E-E-A-T Ready</strong><br>
  Built for YMYL content sites by <a href="https://github.com/wasimakramdev">Wasim Akram Developer</a>
</p>

---

## Features

### SEO & Performance
- **JSON-LD Structured Data**: WebSite, Article, BreadcrumbList, CollectionPage, ProfilePage schemas
- **Open Graph & Twitter Cards**: Full meta tag support with image fallbacks
- **Semantic HTML5**: Proper heading hierarchy, ARIA labels, skip-link navigation
- **Reading Progress Bar**: Visual progress indicator for long-form content
- **Table of Contents**: Auto-generated from H2/H3 headings with active scroll tracking
- **Breadcrumbs**: SEO-friendly breadcrumb navigation on all pages
- **Canonical URLs & RSS**: Proper linking and feed support

### Design & UX
- **6 Accent Colors**: Blue, Green, Red, Purple, Orange, Teal (configurable via Ghost Admin)
- **Dark Mode**: System-aware with manual toggle, persisted in localStorage
- **3 Feed Layouts**: Grid, List, Compact (switchable from Ghost Admin)
- **Mobile-First Responsive**: Optimized for mobile, tablet, and desktop
- **Sticky Header**: Blur backdrop header with scroll detection
- **Hero Search**: Prominent search bar on homepage with Ghost API integration
- **Smooth Animations**: Fade-in card animations, hover effects, prefers-reduced-motion support
- **Print Styles**: Clean, readable print output

### E-E-A-T & YMYL
- **Trust Indicators**: Fact-Checked, Verified Sources, Expert Reviewed badges
- **Disclaimer Box**: Legal compliance for informational content
- **Enhanced Author Bio**: With credentials, location, and website links
- **Last Updated Signal**: Shows article freshness on post headers

### Accessibility
- WCAG 2.1 AA compliant
- Keyboard navigation support
- ARIA labels and roles throughout
- Skip-to-content link
- Focus management for modals
- Reduced motion media query support

### Content Features
- **Built-in Search Modal**: Ghost API-powered instant search (Ctrl+K shortcut)
- **Featured Post Section**: Highlighted post on homepage
- **Related Posts**: Auto-suggested articles by tag
- **Newsletter CTA**: Membership signup integration
- **Share Buttons**: X/Twitter, Facebook, LinkedIn, Copy Link
- **Copy Link on Heading Click**: Easy section linking
- **Lazy Loading Images**: IntersectionObserver-based for performance

## Configuration

All settings are available in **Ghost Admin > Settings > Theme**:

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Feed Layout | Select | Grid | Card layout: Grid, List, or Compact |
| Accent Color | Select | Blue | Theme accent: Blue, Green, Red, Purple, Orange, Teal |
| Show Author Bio | Toggle | On | Display author information below posts |
| Show Related Posts | Toggle | On | Show related articles by tag |
| Show Table of Contents | Toggle | On | Auto-generate TOC from headings |
| Show Reading Progress | Toggle | On | Display reading progress bar |
| Show Share Buttons | Toggle | On | Social sharing buttons on posts |
| Show Newsletter CTA | Toggle | On | Membership signup section |
| Show Trust Badge | Toggle | On | E-E-A-T trust indicators on homepage |
| Show Disclaimer | Toggle | On | Legal disclaimer on posts |

## Installation

### Via Ghost Admin
1. Go to **Settings > Design > Upload theme**
2. Upload the `lexington.zip` file
3. Click **Activate**

### Via CLI
```bash
# If theme is in a subdirectory
ghost install lexington /path/to/lexington-ghost-theme

# Restart Ghost
ghost restart
```

## File Structure

```
lexington-ghost-theme/
├── assets/
│   ├── css/
│   │   └── screen.css          # Complete responsive stylesheet
│   └── js/
│       └── main.min.js         # Theme JavaScript
├── members/
│   ├── account.hbs             # Account management page
│   ├── login.hbs               # Sign in page
│   └── signup.hbs              # Sign up page
├── partials/
│   ├── author-bio.hbs          # Author profile card (E-E-A-T)
│   ├── breadcrumbs.hbs         # Breadcrumb navigation
│   ├── disclaimer-box.hbs      # YMYL legal disclaimer
│   ├── footer.hbs              # Site footer
│   ├── head.hbs                # SEO meta + critical CSS
│   ├── header.hbs              # Sticky header with nav
│   ├── navigation.hbs          # Desktop + mobile navigation
│   ├── newsletter-cta.hbs      # Membership CTA
│   ├── pagination.hbs          # Page navigation
│   ├── post-card.hbs           # Article card
│   ├── post-card-featured.hbs  # Featured article card
│   ├── related-posts.hbs       # Related articles
│   ├── schema-markup.hbs       # JSON-LD structured data
│   ├── search-modal.hbs        # Search overlay
│   ├── share-buttons.hbs       # Social sharing
│   ├── table-of-contents.hbs   # Auto-generated TOC
│   └── trust-indicators.hbs    # E-E-A-T trust badges
├── author.hbs                  # Author archive page
├── default.hbs                 # Base template
├── error.hbs                   # 404/error page
├── index.hbs                   # Homepage
├── package.json                # Theme metadata & config
├── page.hbs                    # Static page
├── post.hbs                    # Single post
└── tag.hbs                     # Tag archive page
```

## Requirements

- Ghost 5.0.0 or higher
- Modern browser (Chrome, Firefox, Safari, Edge)

## Author

**Wasim Akram Developer**
Email: prodigitalwasim@gmail.com
GitHub: [wasimakramdev](https://github.com/wasimakramdev)

## License

MIT License - see [LICENSE](LICENSE) file for details.

---

<p align="center">
  Built with ❤️ for the Ghost community
</p>
