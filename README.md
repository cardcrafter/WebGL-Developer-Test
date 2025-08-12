# WebGL Developer Test

A modern 3D web application built with React, Three.js, and WebGL technologies. This project demonstrates advanced 3D rendering capabilities with interactive model viewing, animations, and post-processing effects.

## 🚀 Features

- **3D Model Viewer**: Interactive 3D model rendering with GLB format support
- **Real-time Animations**: Smooth model animations with GSAP integration
- **Post-processing Effects**: Bloom effects and environment lighting
- **Responsive Design**: Modern UI with Tailwind CSS
- **Scroll-based Interactions**: Dynamic 3D scene manipulation based on scroll position
- **Performance Optimized**: Efficient rendering with React Three Fiber

## 🛠️ Tech Stack

- **Frontend**: React 18 + TypeScript
- **3D Graphics**: Three.js + React Three Fiber
- **Animations**: GSAP (GreenSock)
- **Styling**: Tailwind CSS + SASS
- **Build Tool**: Create React App
- **Package Manager**: npm/yarn

## 📦 Dependencies

### Core Dependencies
- `@react-three/fiber` - React renderer for Three.js
- `@react-three/drei` - Useful helpers for React Three Fiber
- `@react-three/postprocessing` - Post-processing effects
- `three` - 3D graphics library
- `gsap` - Professional animation library
- `react` & `react-dom` - React framework

### Development Dependencies
- `typescript` - Type safety
- `tailwindcss` - Utility-first CSS framework
- `eslint` & `prettier` - Code quality tools

## 🚀 Getting Started

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd WebGL-Developer-Test
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to view the application

## 📁 Project Structure

```
src/
├── components/
│   ├── Loading/          # Loading component
│   └── Model/            # 3D model component
├── layout/
│   ├── Configurator/     # Main app layout
│   └── Scene/            # 3D scene setup
├── App.tsx               # Main application component
└── index.tsx             # Application entry point

public/
└── model/
    └── object.glb        # 3D model file
```

## 🎮 Usage

### Basic Navigation
- **Scroll Down**: The 3D scene rotates based on scroll position
- **Mouse Interaction**: Orbit controls for camera manipulation
- **Viewport**: Explore different sections of the application

### 3D Scene Features
- **Model Animation**: Automatic model animations on load
- **Environment**: Night-time lighting preset
- **Effects**: Bloom post-processing for enhanced visuals
- **Particles**: Sparkle effects for atmosphere

## 🧪 Testing

Run the test suite:
```bash
npm test
# or
yarn test
```

## 🏗️ Building for Production

Create a production build:
```bash
npm run build
# or
yarn build
```

## 🔧 Available Scripts

- `npm start` - Start development server
- `npm build` - Build for production
- `npm test` - Run test suite
- `npm run lint` - Run ESLint
- `npm run eject` - Eject from Create React App (irreversible)

## 🌟 Key Features Explained

### 3D Model Rendering
The application uses React Three Fiber to render 3D models with:
- Automatic model loading from GLB files
- Smooth animations and transitions
- Optimized rendering performance

### Scroll-based Interactions
GSAP ScrollTrigger integration enables:
- Dynamic 3D scene rotation based on scroll
- Smooth, performant animations
- Responsive user experience

### Post-processing Pipeline
Advanced visual effects including:
- Bloom lighting effects
- Environment-based lighting
- Optimized rendering pipeline

## 🎨 Customization

### Adding New Models
1. Place your GLB file in `public/model/`
2. Update the model path in `src/components/Model/index.tsx`
3. Adjust scale and rotation as needed

### Modifying Effects
- Edit post-processing effects in `src/layout/Scene/index.tsx`
- Adjust lighting parameters in the Scene component
- Modify animation timelines in the GSAP configuration

## 🐛 Troubleshooting

### Common Issues
- **Model not loading**: Ensure the GLB file exists in the correct path
- **Performance issues**: Check browser console for WebGL support
- **Build errors**: Verify all dependencies are properly installed

### Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge

## 📝 License

This project is private and proprietary.

## 👨‍💻 Author

**Evgenii Petrukhin**
- Email: evgeniipetrukhin90@gmail.com

## 🤝 Contributing

This is a test project for WebGL development assessment. For questions or issues, please contact the author.

---

**Note**: This project demonstrates advanced WebGL and 3D web development capabilities using modern web technologies. It serves as a showcase for interactive 3D applications in the browser.
