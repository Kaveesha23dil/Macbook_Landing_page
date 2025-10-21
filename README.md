# MacBook Pro Landing Page

A stunning, modern landing page for MacBook Pro featuring interactive 3D models, smooth animations, and an Apple-inspired design. Built with React, Three.js, and GSAP.

## Features

- **Interactive 3D Models**: Explore MacBook Pro models in 3D with React Three Fiber
- **Smooth Animations**: Beautiful scroll-triggered animations using GSAP
- **Responsive Design**: Optimized for all screen sizes from mobile to desktop
- **Modern Tech Stack**: React 19, Vite, Tailwind CSS 4, Three.js
- **Apple-Inspired UI**: Sleek, minimalist design following Apple's design language

## Tech Stack

- **React 19** - Latest React version with modern features
- **Vite** - Fast build tool and development server
- **Three.js & React Three Fiber** - 3D graphics and models
- **GSAP** - Professional-grade animation library
- **Tailwind CSS 4** - Utility-first CSS framework
- **Zustand** - Lightweight state management
- **React Three Drei** - Useful helpers for React Three Fiber

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Kaveesha23dil/Macbook_Landing_page.git
cd Macbook_Landing_page
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Project Structure

```
macbook-landing-page/
├── public/
│   ├── models/          # 3D model files (.glb)
│   ├── videos/          # Video assets
│   ├── fonts/           # Custom fonts
│   └── images/          # Image assets
├── src/
│   ├── components/
│   │   ├── models/      # 3D model components
│   │   ├── three/       # Three.js related components
│   │   ├── Hero.jsx     # Hero section
│   │   ├── Navbar.jsx   # Navigation bar
│   │   ├── ProductViewer.jsx  # 3D product viewer
│   │   └── Showcase.jsx # Feature showcase
│   ├── constants/       # App constants
│   ├── store/           # State management
│   ├── App.jsx          # Main app component
│   ├── main.jsx         # Entry point
│   └── index.css        # Global styles
└── package.json
```

## Sections

1. **Hero** - Eye-catching introduction with video background
2. **Product Viewer** - Interactive 3D MacBook models with color and size options
3. **Showcase** - M4 chip features with scroll animations
4. **Performance** - Performance metrics and capabilities
5. **Features** - Key features with videos and icons
6. **Highlights** - Product highlights in a masonry layout

## Customization

### Colors

Edit the color palette in `src/index.css`:
```css
@theme {
  --color-primary: #0071e3;
  --color-dark-100: #86868b;
  --color-dark-200: #2e2e30;
  --color-light-100: #adb5bd;
}
```

### 3D Models

Replace models in `/public/models/` with your own `.glb` files and update references in the model components.

## Deployment

### Build for Production
```bash
npm run build
```

The build output will be in the `dist/` folder, ready to deploy to any static hosting service.

### Deploy to Vercel
```bash
npm install -g vercel
vercel
```

### Deploy to Netlify
```bash
npm install -g netlify-cli
netlify deploy --prod
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Design inspiration from Apple Inc.
- 3D models and assets created for educational purposes
- Animation techniques inspired by modern web design trends

## Author

**Kaveesha Dilshan**
- GitHub: [@Kaveesha23dil](https://github.com/Kaveesha23dil)

---

Made with ❤️ using React and Three.js