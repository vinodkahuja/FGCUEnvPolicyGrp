# FGCU-Style Academic Website

A Jekyll-based static website with FGCU styling for GitHub Pages.

## Setup Instructions

1. **Fork or create repository**: Name it `[username].github.io`
2. **Enable GitHub Pages**: Settings → Pages → Source: main branch
3. **Wait 1-2 minutes** for GitHub to build your site
4. **Visit**: `https://[username].github.io`

## Editing Content

### Pages
Edit files in `_pages/` directory:
- `about.md` - About page
- `programs.md` - Programs page
- `research.md` - Research page
- `contact.md` - Contact information

### Homepage
Edit `index.md` in the root directory

### Navigation Menu
Edit `_data/navigation.yml` to add/remove menu items

### Blog Posts
Create new files in `_posts/` with format: `YYYY-MM-DD-title.md`

### Styling
Modify `assets/css/style.css` to change colors and design

### Site Settings
Edit `_config.yml` for site-wide settings (title, URL, etc.)

## Local Development

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# View at http://localhost:4000
```

## Customization

### Change Colors
Edit CSS variables in `assets/css/style.css`:
```css
:root {
  --fgcu-blue: #00396D;
  --fgcu-green: #00B388;
  /* Add your colors */
}
```

### Add Logo
1. Place logo image in `assets/images/`
2. Update `_includes/header.html`

## Support

For Jekyll documentation: https://jekyllrb.com/docs/
For GitHub Pages: https://docs.github.com/en/pages