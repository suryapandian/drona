# Drona Academy Website

Static website for [Drona Academy](https://drona-academy.netlify.app) built with Hugo and the [Paige theme](https://github.com/willfaught/paige).

[![Netlify Status](https://api.netlify.com/api/v1/badges/7859430e-4479-4880-9c9d-f2c79a3029c5/deploy-status)](https://app.netlify.com/sites/drona-academy/deploys)

## About Drona Academy

Drona Academy is a coaching center in Sivakasi that helps people from rural backgrounds excel in life through academics and social activities. We offer:

- Tuitions in Physics, Chemistry, and Mathematics for school students  
- Coaching for Bank Exams, Group Exams, and UPSC Exams for graduates and college students
- Periodic tests, feedback, and course materials
- Volunteering activities like blood donation and scribing for blind students

## Development

### Prerequisites

- [Hugo Extended](https://gohugo.io/installation/) (v0.119.0 or later)
- [Dart Sass](https://sass-lang.com/install)

### Installation

#### macOS
```bash
brew install hugo
brew install sass/sass/sass
```

#### Using npm (alternative)
```bash
npm install
```

### Running Locally

```bash
# Start development server
hugo server

# Or using npm
npm run dev

# Build for production  
hugo --gc --minify

# Or using npm
npm run build
```

### Project Structure

```
├── content/           # Markdown content files
│   ├── images/       # Image assets organized by category
│   │   ├── general/     # General website images
│   │   ├── monthly-updates/  # Monthly update images
│   │   └── nandana/     # Nandana bags product images
├── layouts/          # Custom Hugo layouts
├── static/           # Static assets (favicons, etc.)
├── themes/paige/     # Paige theme submodule
└── hugo.toml         # Hugo configuration
```

## Deployment

The site is automatically deployed to Netlify when changes are pushed to the main branch.
