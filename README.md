# Steel Panel Tank - Angle-Stay Layout Editor

A 2D/3D interactive editor for designing reinforcement stay layouts on cylindrical tank walls.

## Setup Instructions

### 1. Install Dependencies
```bash
npm install
```

### 2. Start Development Server
```bash
npm run dev
```
The app will open at `http://localhost:5173`

### 3. Build for Production
```bash
npm run build
```

## Features

- **2D Top View (Plan)**: Grid-based panel system with configurable dimensions
- **3D Isometric View**: Orbitable 3D visualization with height control
- **Editing Tools**: Draw, Line, and Erase tools
- **Stay Types**: Corner, Main, Opposite, and Tie stays with color coding
- **Export**: Save layouts as JSON, SVG, or PNG

## How to Use

1. **Draw**: Click cells to toggle diagonal stays
2. **Line**: Click two nodes to connect with a stay
3. **Erase**: Click a stay to remove it
4. **3D Navigation**: Drag the 3D view to orbit around the tank
5. **Top/Bottom**: Switch between tank top and bottom for cross-plane stays
6. **Adjustments**: Use the controls to resize tank dimensions

## Technologies

- React 18
- Vite
- Tailwind CSS
- Lucide React Icons
