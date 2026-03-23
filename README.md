# Neural Interface Design - BCI Landing Page

A premium, dark-themed landing page for an AI-powered Brain Computer Interface design agency. Built with React, Vite, TypeScript, Tailwind CSS, and Framer Motion.

## Features

- **Premium Dark Design**: Apple-inspired aesthetic with custom "liquid glass" morphism effects
- **Smooth Animations**: BlurText animations and Framer Motion transitions
- **Video Backgrounds**: HLS video streaming with adaptive playback
- **Responsive Layout**: Fully responsive across all device sizes
- **BCI-Themed Content**: Specialized for Brain Computer Interface industry

## Technology Stack

- **React 18** - UI framework
- **Vite** - Build tool and dev server
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first styling
- **Framer Motion** - Smooth animations
- **HLS.js** - Video streaming support
- **Lucide React** - Icon library

## Design System

### Fonts
- **Instrument Serif** (italic) - Headings
- **Barlow** (300, 400, 500, 600) - Body text

### Color Palette
- Pure black background (`#000000`)
- White text with various opacity levels
- Custom liquid glass effects with gradient borders

### Components
- Liquid glass cards (subtle and strong variants)
- Rounded full buttons
- Animated blur text
- Video backgrounds with fade overlays

## Getting Started

### Prerequisites
- Node.js 18+ and npm

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

4. Preview production build:
```bash
npm run preview
```

## Project Structure

```
src/
├── components/
│   └── BlurText.tsx       # Animated text component
├── lib/
│   └── utils.ts           # Utility functions
├── App.tsx                # Main application component
├── main.tsx               # Application entry point
└── index.css              # Global styles and liquid glass effects
```

## Sections

1. **Navbar** - Fixed navigation with liquid glass design
2. **Hero** - Large hero section with video background and animated headline
3. **Partners** - Trusted partner logos bar
4. **How It Works** - Process explanation with HLS video
5. **Features Chess** - Alternating feature showcase
6. **Features Grid** - 4-column feature highlights
7. **Stats** - Key metrics with video background
8. **Testimonials** - Client testimonials in 3-column grid
9. **CTA Footer** - Call-to-action and footer links

## Customization

### Colors
Edit CSS variables in `src/index.css`:
```css
:root {
  --background: 213 45% 67%;
  --foreground: 0 0% 100%;
  --primary: 0 0% 100%;
  --primary-foreground: 213 45% 67%;
  --border: 0 0% 100% / 0.2;
  --radius: 9999px;
}
```

### Fonts
Update Google Fonts import in `index.html` and Tailwind config in `tailwind.config.js`.

### Content
All content is in `src/App.tsx`. Edit text, images, and videos directly in the component sections.

## License

MIT
