# 3D Controller Configurator

> This project was created as a practical demonstration for the master's thesis: "The Use of 3D Technology in Web Design and Development"

This application showcases how seamlessly 3D models created in Blender can be integrated into modern web applications. Using React Three Fiber, the project demonstrates that bringing sophisticated 3D visualizations to the web is more accessible than ever before.

## Live Demo

https://r3f-controller-configurator-2025.vercel.app/

## Visual Documentation

Blender Workflow

![26](https://github.com/user-attachments/assets/540ee8b6-8112-4078-a802-a600f2b74b61)

_Game controller mesh in Blender before applying modifiers - showing the base geometry and wireframe structure used as the foundation for the 3D model._

---

![27](https://github.com/user-attachments/assets/b2ffba61-8438-4f2c-a5f3-9412dd6c005d)

_Final controller model in Blender after modifier application - displaying the refined mesh topology with subdivision surface and other modifiers applied, ready for web export._

---

<img width="1383" height="707" alt="29" src="https://github.com/user-attachments/assets/b0ddff7b-77f9-46d1-9fdd-a8d91d04fb61" />

_Website interface collage showcasing four different controller color variations - demonstrating the real-time customization capabilities and interactive 3D visualization in the browser._

## Features

* **Interactive 3D Visualization** - Smooth orbit controls with optimized viewing angles
* **Real-time Customization** - Modify 7 different controller parts instantly
  * Body (Base shell)
  * Front Panel
  * Touchpad
  * LED Outline
  * Buttons
  * Analog Sticks
  * Triggers
* **Color Palette** - 8 color options per component for extensive customization

## Technology Stack

* React 19.0
* React Three Fiber 9.1.0
* Three.js 0.174.0
* @react-three/drei 9.103.0 
* Vite 5.4.19 

## From Blender to Web: The Workflow

This project demonstrates how straightforward it is to bring Blender models to the web:

1. Model in Blender - Create and refine your 3D model with modifiers, materials, and proper naming conventions
2. Export as GLB - Use Blender's built-in glTF 2.0 exporter for optimized web delivery
3. Load with useGLTF - React Three Fiber's `useGLTF` hook handles model loading seamlessly
4. Manipulate Materials - Access and modify materials programmatically through Three.js
5. Deploy - Standard web deployment process - no special 3D hosting required

The entire integration requires minimal code, making 3D web experiences accessible to developers familiar with React.

## Local Development
Prerequisites
* Node.js (v18 or higher recommended)
* npm or yarn

Installation:

```
# Clone the repository
git clone https://github.com/yourusername/r3f-controller-configurator-2025.git

# Navigate to project directory
cd r3f-controller-configurator-2025

# Install dependencies
npm install
```

Running the Development Server
```
npm run dev
```

The application will be available at `http://localhost:5173`

---

Building for Production
```
npm run build
```
The optimized build will be output to the docs directory.

## License

**Created as part of academic research (2025)**

This project is developed as part of a Master's Thesis. - *The Use of 3D Technology in Web Design and Development*

The goal was to demonstrate that modern web technologies like React Three Fiber have dramatically lowered the barrier to entry for 3D web experiences. What once required specialized plugins or complex WebGL programming can now be achieved with familiar React patterns and straightforward model imports.

Distributed under the **MIT License**. Feel free to use, modify, and distribute this software for both academic and commercial purposes, provided that the original copyright notice is included.
