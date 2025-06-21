# React + TypeScript + Vite

A modern React application built with TypeScript and Vite for fast development and optimal performance.

## 🚀 Live Demo

View the live application at: [https://ispeakeasy.github.io/react](https://ispeakeasy.github.io/react)

## 🛠️ Tech Stack

- **React 19** - Modern React with latest features
- **TypeScript** - Type-safe JavaScript
- **Vite** - Fast build tool and dev server
- **CSS3** - Styling

## 📋 Features

- ⚡ Lightning fast development with Vite HMR
- 🔷 Full TypeScript support with strict type checking
- 📱 Responsive design
- 🚀 Optimized production builds
- 📦 Automatic GitHub Pages deployment

## 🏃‍♂️ Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ispeakeasy/react.git
cd react
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

Open [http://localhost:5173/react/](http://localhost:5173/react/) in your browser.

## 📜 Available Scripts

### `npm run dev`
Starts the development server with hot module replacement.
- Local: http://localhost:5173/react/
- Super fast startup (~300ms)

### `npm run build`
Builds the app for production to the `dist` folder.
- Optimized and minified
- Ready for deployment

### `npm run preview`
Previews the production build locally.
- Local: http://localhost:4173/react/

### `npm run deploy`
Builds and deploys the app to GitHub Pages.

## 🏗️ Project Structure

```
src/
├── components/
│   └── MyPage.tsx      # Custom page component
├── App.tsx             # Main App component
├── main.tsx            # Application entry point
├── index.css           # Global styles
└── App.css             # App-specific styles
```

## 🔧 Configuration

- **TypeScript**: `tsconfig.json` - Strict type checking enabled
- **Vite**: `vite.config.ts` - Build configuration
- **GitHub Pages**: Configured with `/react/` base path

## 🚀 Deployment

This project is automatically deployed to GitHub Pages when changes are pushed to the main branch.

Manual deployment:
```bash
npm run deploy
```

## 📈 Performance

- **Build time**: ~1.2s (vs 30+ seconds with CRA)
- **Dev server startup**: ~300ms
- **Bundle size**: ~191KB (gzipped: ~61KB)
- **Hot reload**: Instant

## 🔄 Migration History

This project was migrated from Create React App to Vite + TypeScript for better performance and developer experience.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
