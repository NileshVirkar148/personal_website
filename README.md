# Personal Website - Eccentric Escape

A modern personal website built with Astro, featuring a profile, resume, and blog sections.

## 🚀 Features

- **Home Page**: Welcome section with navigation to main areas
- **Profile Page**: Personal information, skills, and contact details
- **Resume Page**: Professional experience, education, and projects
- **Blog**: Content management system for articles and posts
- **Responsive Design**: Mobile-friendly layout
- **Fast Performance**: Built with Astro for optimal loading speeds

## 🛠️ Tech Stack

- **Framework**: Astro 6.1.5
- **Styling**: CSS (with responsive design)
- **Content**: Markdown for blog posts
- **Build Tool**: Vite

## 📁 Project Structure

```
/
├── public/
│   ├── favicon.ico
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Welcome.astro (legacy component)
│   ├── content/
│   │   └── blog/ (blog posts in Markdown)
│   ├── layouts/
│   │   └── Layout.astro (main layout with navigation)
│   └── pages/
│       ├── index.astro (home page)
│       ├── profile.astro
│       ├── resume.astro
│       └── blog/
│           ├── index.astro (blog listing)
│           └── [...slug].astro (individual blog posts)
├── astro.config.mjs
├── package.json
├── src/
│   └── content.config.ts (content collections config)
└── tsconfig.json
```

## 🏃‍♂️ Getting Started

### Prerequisites

- Node.js 22.12.0 or higher
- npm

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

### Development

Start the development server:
```bash
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) in your browser.

### Build

Build for production:
```bash
npm run build
```

Preview the production build:
```bash
npm run preview
```

## 📝 Customization

### Personal Information

Update the following files with your information:

- `src/pages/index.astro`: Home page content
- `src/pages/profile.astro`: Personal details, skills, contact info
- `src/pages/resume.astro`: Work experience, education, projects

### Blog Posts

Add new blog posts in `src/content/blog/` as Markdown files with frontmatter:

```markdown
---
title: "Your Blog Post Title"
description: "Brief description of the post"
pubDate: 2024-04-11
updatedDate: 2024-04-11
heroImage: "/path/to/image.jpg"
---

Your blog post content here...
```

### Styling

Modify styles in the `<style>` sections of each Astro component or create separate CSS files.

## 📄 Content Collections

The blog uses Astro's content collections feature. Configuration is in `src/content.config.ts`.

## 🚀 Deployment

The site can be deployed to any static hosting service like:

- Netlify
- Vercel
- GitHub Pages
- AWS S3 + CloudFront

Build the site with `npm run build` and deploy the `dist/` folder.

## 🤝 Contributing

This is a personal website template. Feel free to modify and adapt it for your needs!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
│   │   └── Welcome.astro
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
