# Renny's Blog

This is your personal Jekyll blog with dark mode and improved styling.

## Features

- ✨ **Dark Mode by Default**: Toggle between light and dark themes with the button in the top-right corner
- 📱 **Responsive Design**: Looks great on all devices
- 🖼️ **Optimized Profile Picture**: Properly sized profile image with hover effects
- 🎨 **Clean Typography**: Improved readability and spacing
- ⚡ **Fast Loading**: Optimized CSS and JavaScript

## How to Use

### Writing New Posts

1. Create a new file in the `_posts/` directory
2. Name it using the format: `YYYY-MM-DD-title.markdown`
3. Start with the front matter:

```markdown
---
layout: post
title: "Your Post Title"
date: 2025-10-02 12:00:00 +0000
categories: your categories here
---

Your content here...
```

### Editing Pages

- **About Page**: Edit `about.markdown`
- **Home Page**: Edit `index.markdown`

### Managing the Site

- **Configuration**: Edit `_config.yml` for site-wide settings
- **Profile Picture**: Replace `assets/imgs/profile.jpeg` with your photo
- **Styling**: Custom styles are in `assets/main.scss`

### Running Locally

```bash
# Install dependencies
bundle install

# Start the development server
bundle exec jekyll serve

# View at http://localhost:4000
```

### Publishing to GitHub Pages

Simply push your changes to the `main` branch - GitHub Pages will automatically build and deploy your site.

## File Structure

```
├── _config.yml          # Site configuration
├── _posts/              # Blog posts
├── _layouts/            # Custom page layouts
├── _includes/           # Reusable components
├── assets/
│   ├── main.scss        # Custom styles
│   ├── js/
│   │   └── theme-toggle.js  # Dark mode functionality
│   └── imgs/
│       └── profile.jpeg # Your profile picture
├── about.markdown       # About page
└── index.markdown       # Home page
```

## Tips

- Keep post filenames consistent with the date format
- Use descriptive titles and categories
- Preview changes locally before pushing to GitHub
- The dark theme preference is saved in localStorage
- Images are automatically responsive

Enjoy writing! 🚀
