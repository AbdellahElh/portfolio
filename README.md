# Portfolio Website

A modern, responsive portfolio website built with Astro, TypeScript, and Tailwind CSS. Features dynamic GitHub integration, mobile-optimized design, and professional project showcases.

## 🚀 Features

- **Modern Tech Stack**: Built with Astro 4.16.18, TypeScript, and Tailwind CSS
- **GitHub Integration**: Automatically syncs projects from GitHub API
- **Mobile Responsive**: Optimized for all device sizes with responsive navigation
- **Certificate Management**: Displays certifications with PDF downloads
- **Professional Design**: Clean, accessible design with dark mode support
- **SEO Optimized**: Proper meta tags, canonical URLs, and structured content

## 🛠️ Technologies

- **Frontend**: Astro, TypeScript, Tailwind CSS
- **Deployment**: Vercel
- **APIs**: GitHub REST API for project data
- **Icons**: Custom SVG icon system
- **Styling**: Utility-first CSS with Tailwind

## 🎯 Live Demo

Visit the live portfolio: [abdellah-elhalimi.vercel.app](https://abdellah-elhalimi.vercel.app)

## 📱 Mobile Responsiveness

- Compact navbar with smaller brand text on mobile
- Icon-only GitHub buttons on mobile devices  
- Responsive project grid layout
- Touch-friendly interface design

## 🏗️ Project Structure

```
/
├── public/
│   ├── certificates/     # PDF certificates
│   ├── imgs/            # Project images
│   └── favicon.svg      # Site favicon
├── src/
│   ├── components/      # Reusable Astro components
│   ├── layouts/         # Page layouts
│   ├── lib/            # GitHub API integration
│   ├── pages/          # Site pages
│   └── styles/         # Global styles
├── astro.config.mjs    # Astro configuration
├── tailwind.config.mjs # Tailwind configuration
└── tsconfig.json       # TypeScript configuration
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/AbdellahElh/portfolio.git
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## 📦 Key Components

### ProjectCard
Displays GitHub projects with:
- Project descriptions and metadata
- Technology tags
- GitHub and live preview links
- Mobile-responsive button layout

### CertificateCard  
Shows professional certifications with:
- Credential information
- PDF download functionality
- External verification links

### Header
Navigation component featuring:
- Responsive brand text
- Smooth scroll navigation
- Mobile-optimized GitHub button

## 🎨 Customization

The portfolio is highly customizable through:
- `src/lib/github.ts` - Project data and descriptions
- `tailwind.config.mjs` - Color schemes and styling
- `src/components/` - Component modifications
- `src/pages/index.astro` - Content and layout

## 📊 Performance

- **Lighthouse Score**: 100/100 across all metrics
- **Built with Astro**: Near-zero JavaScript by default
- **Optimized Images**: Responsive image handling
- **Fast Loading**: Minimal bundle size and efficient code splitting

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📬 Contact

- **Email**: abdellah.elhalimimerroun@student.hogent.be
- **GitHub**: [@AbdellahElh](https://github.com/AbdellahElh)
- **Portfolio**: [abdellah-elhalimi.vercel.app](https://abdellah-elhalimi.vercel.app)
