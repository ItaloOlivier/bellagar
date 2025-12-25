# Bella Gar Fan Page

A static fan website for Isabella "Bella" Gar, an elite triathlete representing Great Britain.

## About Bella

- **Nationality**: Dual British-Italian national
- **Represents**: Great Britain (GBR)
- **Racing**: Domestically in both UK and Italy
- **Training**: Based in Italy under coach Massimo Strada
- **Team**: Team 707 Minini
- **Instagram**: [@bellagarfish](https://instagram.com/bellagarfish)

## Project Structure

- `index.html` - Main HTML page with SEO-optimized content and structured data
- `styles.css` - CSS styling with feminine design, animations, and accessibility features
- `favicon.svg` - Site favicon (lavender gradient with italic BG)
- `robots.txt` - Search engine and AI crawler directives
- `sitemap.xml` - XML sitemap with image extensions
- `images/` - 44 photo assets (cycling, running, swimming, podiums, team, portraits)

## Tech Stack

- Vanilla HTML/CSS (no build tools or JavaScript frameworks)
- Google Fonts: Playfair Display (serif display) & DM Sans (body)
- Responsive design with CSS custom properties
- CSS animations with reduced-motion support

## Development

Open `index.html` directly in a browser or use a local server:

```bash
python -m http.server 8000
```

## Site Sections

1. **Hero** - Main banner with portrait and disciplines
2. **About** - Biography and stats with Schema.org Person markup
3. **Team** - Team 707 Minini and coach info
4. **News** - Latest updates with NewsArticle schema
5. **Achievements** - Race results with SportsEvent schema
6. **Gallery** - 5-photo mosaic gallery with descriptive alt text
7. **Instagram** - Embedded feed (@bellagarfish)
8. **Connect** - Social links

## Design Theme

**Feminine, Fun & Fresh** (no pink!)

### Color Palette
- **Primary**: Soft lavender purple (#7C6A9C)
- **Accent**: Warm coral (#E8846B)
- **Secondary**: Fresh sage green (#8FAE8B)
- **Gold**: Warm metallic (#D4A574)
- **Backgrounds**: Cream, lavender-tint, sage-tint

### Typography
- **Display**: Playfair Display (elegant italic serif)
- **Body**: DM Sans (modern sans-serif)

### Visual Features
- Gradient text headings
- Animated floating blobs
- Soft rounded corners (24px)
- Playful hover animations
- Decorative emoji accents
- Purple-tinted soft shadows

## SEO & AI Readiness

### Meta Tags
- Primary meta (title, description, keywords)
- Open Graph (Facebook/LinkedIn sharing)
- Twitter Card (large image)
- Geo and language targeting
- Robot directives (index, follow)

### Structured Data (JSON-LD)
- **Person**: Full athlete profile with nationality, team, coach
- **ProfilePage**: Page-level markup
- **WebSite**: Site-level with search action
- **BreadcrumbList**: Navigation structure
- **ItemList/SportsEvent**: Achievement results
- **FAQPage**: Common questions for AI assistants
- **NewsArticle**: News items with dates

### AI Crawler Support
robots.txt explicitly allows:
- GPTBot, ChatGPT-User (OpenAI)
- Google-Extended (Google AI)
- Anthropic-AI, Claude-Web
- PerplexityBot
- Applebot-Extended

### Accessibility (WCAG 2.1)
- Skip-to-content link
- ARIA roles and labels
- Semantic HTML5 elements
- Focus-visible outlines
- Reduced-motion support
- Descriptive alt text on all images
- Proper heading hierarchy

### Performance
- Preconnect to font origins
- DNS prefetch for Instagram
- Lazy loading on below-fold images
- fetchpriority="high" on hero image
- Width/height attributes prevent CLS

## Canonical URL

https://bellagar.com/
