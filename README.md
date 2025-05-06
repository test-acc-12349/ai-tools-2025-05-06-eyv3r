# AI Tools Directory 🤖

> The ultimate directory of AI tools and resources for professionals and enthusiasts.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR-NETLIFY-ID/deploy-status)](https://app.netlify.com/sites/your-site/deploys)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Directory Structure](#directory-structure)
- [Customization](#customization)
  - [Adding Directory Items](#adding-directory-items)
  - [Modifying Categories](#modifying-categories)
  - [Updating Hero Section](#updating-hero-section)
  - [Styling Changes](#styling-changes)
- [Deployment](#deployment)
- [Domain Setup](#domain-setup)
- [Troubleshooting](#troubleshooting)
- [Resources](#resources)
- [Support](#support)

## Overview

AI Tools Directory is a responsive, modern directory website showcasing various artificial intelligence tools and resources. Built with a clean 3-column grid layout, it offers easy navigation and filtering capabilities.

## Features

- 🎯 Responsive 3-column grid layout
- 🔍 Search functionality
- 🏷️ Category filtering
- 📱 Mobile-friendly design
- 🚀 Fast loading times
- 🎨 Customizable styling
- 📊 SEO optimized

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ai-tools-directory.git

# Navigate to project directory
cd ai-tools-directory

# Install dependencies
npm install

# Start development server
npm run dev
```

## Directory Structure

```
ai-tools-directory/
├── src/
│   ├── components/
│   │   ├── Card.js
│   │   ├── Hero.js
│   │   └── Navigation.js
│   ├── data/
│   │   └── directory-items.json
│   ├── styles/
│   │   └── main.css
│   └── pages/
├── public/
│   └── images/
├── package.json
└── README.md
```

## Customization

### Adding Directory Items

Add new items to `src/data/directory-items.json`:

```json
{
  "id": "unique-id",
  "title": "Tool Name",
  "description": "Tool description",
  "category": "Category Name",
  "url": "https://toolurl.com",
  "image": "/images/tool-image.png"
}
```

### Modifying Categories

Edit the categories array in `src/data/categories.js`:

```javascript
export const categories = [
  "Machine Learning",
  "Natural Language Processing",
  "Computer Vision",
  "Robotics"
];
```

### Updating Hero Section

Modify the hero section in `src/components/Hero.js`:

```javascript
<div className="hero">
  <h1>Your Custom Title</h1>
  <p>Your custom description</p>
</div>
```

### Styling Changes

Customize colors and styles in `src/styles/main.css`:

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --text-color: #your-color;
}
```

## Deployment

1. Create a Netlify account
2. Connect your repository
3. Configure build settings:
   ```
   Build command: npm run build
   Publish directory: dist
   ```
4. Click "Deploy"

## Domain Setup

1. Purchase domain from preferred registrar
2. In Netlify:
   - Go to Domain Settings
   - Click "Add custom domain"
   - Follow DNS configuration instructions

## Troubleshooting

Common issues and solutions:

- **Build Failures**
  - Verify dependencies are installed
  - Check build commands
  - Review error logs

- **Styling Issues**
  - Clear browser cache
  - Check CSS specificity
  - Verify media queries

- **Content Not Updating**
  - Confirm JSON syntax
  - Clear deployment cache
  - Check file paths

## Resources

- [Documentation](https://docs.yoursite.com)
- [Component Library](https://components.yoursite.com)
- [API Reference](https://api.yoursite.com)
- [Style Guide](https://style.yoursite.com)

## Support

- 📧 Email: support@aitools.com
- 💬 Discord: [Join our community](https://discord.gg/aitools)
- 🐦 Twitter: [@AITools](https://twitter.com/aitools)
- 📝 Issues: [GitHub Issues](https://github.com/yourusername/ai-tools-directory/issues)

---

Made with ❤️ by [Your Name](https://yoursite.com)

[⬆ back to top](#ai-tools-directory-)