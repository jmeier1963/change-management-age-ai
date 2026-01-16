# Change Management in the Age of AI - Website

This repository contains the static website for the book "Change Management in the Age of AI" by Johannes Meier, designed to be hosted on GitHub Pages.

## Repository Structure

```
/
├── index.html              # Main landing page
├── book.html               # Detailed book overview
├── author.html             # Author information
├── companion.html          # GitHub companion repository information
├── styles.css              # Website stylesheet
├── book.md                 # Book content (source)
├── change_management_AI.pdf # Full book PDF
├── cover_7.125x10.25in_bleed_300dpi.png  # Book cover image
├── overview.png            # Book overview diagram
├── .nojekyll               # Disable Jekyll processing
└── README.md               # This file
```

## Setting Up GitHub Pages

### Option 1: User/Organization Site
1. Create a repository named `username.github.io` (replace `username` with your GitHub username)
2. Push all files to the `main` branch
3. GitHub Pages will automatically publish the site at `https://username.github.io`

### Option 2: Project Site
1. Create a repository with any name
2. Push all files to the `main` branch
3. Go to repository Settings → Pages
4. Under "Source", select the `main` branch and `/ (root)` folder
5. Click Save
6. Your site will be available at `https://username.github.io/repository-name`

## Files Description

- **index.html**: Landing page with book overview, cover image, and navigation
- **book.html**: Comprehensive book overview with detailed chapter summaries
- **author.html**: Author biography and link to LinkedIn profile
- **companion.html**: Information about the GitHub companion repository
- **styles.css**: Modern, responsive CSS styling
- **.nojekyll**: Ensures GitHub Pages serves files as-is without Jekyll processing

## Images

The website includes:
- Book cover: `cover_7.125x10.25in_bleed_300dpi.png`
- Overview diagram: `overview.png`

Both images are referenced in the HTML files and should be in the root directory.

## GitHub Companion Repository

The companion repository URL and details should be added to `companion.html` and/or this README. The companion repository contains additional resources, tools, and materials to support readers of the book.

## Customization

To customize the website:
1. Edit the HTML files to modify content
2. Modify `styles.css` to change colors, fonts, and layout
3. Update the `.nojekyll` file is already present to disable Jekyll processing

## License

© 2025 Xi GmbH, Gütersloh, Germany
Published by *Xi Press*, an imprint of Xi GmbH
Print Edition ISBN 978-3-00-085630-3
