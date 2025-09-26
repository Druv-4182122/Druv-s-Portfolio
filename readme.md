# Druv's Portfolio

A stunning 3D interactive portfolio website built with React Three Fiber, showcasing creative projects through immersive 3D experiences.

## 🌐 Live Demo

🚀 **[View Live Demo](https://your-portfolio-url.vercel.app)**

*Experience the interactive 3D portfolio in your browser!*

## 📸 Screenshots

### Main Portfolio View
![Portfolio Main View](public/img/portfolio-main.png)

### Interactive 3D Room
![3D Room Environment](public/img/portfolio-room.png)

### Coffee Smoke Effects
![Coffee Smoke Animation](public/img/coffee-smoke.png)

### Mobile Responsive
![Mobile View](public/img/portfolio-mobile.png)

## 🚀 Features

- **Interactive 3D Environment**: Explore a virtual room with interactive elements
- **Smooth Animations**: Powered by GSAP for fluid transitions
- **Modern Tech Stack**: React 19, Three.js, Vite
- **Responsive Design**: Optimized for all devices
- **Coffee Smoke Effects**: Custom GLSL shaders for realistic particle effects
- **Loading Screen**: Engaging loading experience
- **Optimized Assets**: WebP images and compressed 3D models

## 🛠️ Tech Stack

- **Frontend**: React 19, React Three Fiber
- **3D Graphics**: Three.js, React Three Drei
- **3D Modeling**: Blender
- **Animations**: GSAP
- **Shaders**: Custom GLSL shaders
- **Build Tool**: Vite
- **Deployment**: Vercel
- **Asset Optimization**: Draco compression, WebP format

## 📋 Prerequisites

- [Node.js](https://nodejs.org/en/download/) (version 16 or higher)
- npm or yarn package manager

## 🚀 Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/Druv-4182122/Druv-s-Portfolio.git
cd Druv-s-Portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 📜 Available Scripts

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Deploy to Vercel
npm run deploy
```

## 🎯 Project Structure

```
├── public/
│   ├── img/           # Image assets
│   ├── model/         # 3D models
│   ├── Squooshed/     # Optimized textures
│   └── video/         # Video assets
├── src/
│   ├── smokey/        # GLSL shaders
│   ├── app.jsx        # Main app component
│   ├── Model.jsx      # 3D model components
│   └── LoadingScreen.jsx
└── package.json
```

## 🌟 Key Components

- **Interactive Room Model**: 3D room environment with clickable objects
- **Coffee Smoke Effect**: Realistic particle system using custom shaders
- **Loading Screen**: Smooth loading experience with progress indication
- **Responsive 3D Canvas**: Adapts to different screen sizes

## 🚀 Deployment

This project is configured for easy deployment on Vercel:

```bash
npm run deploy
```

## 🎨 Customization

- Modify 3D models in `public/model/`
- Update textures in `public/Squooshed/`
- Customize shaders in `src/smokey/`
- Adjust animations in component files

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

**Note**: WebGL support required for 3D features.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## ‍💻 Author

**Druv**
- GitHub: [@Druv-4182122](https://github.com/Druv-4182122)

---

⭐ Star this repository if you found it helpful!
