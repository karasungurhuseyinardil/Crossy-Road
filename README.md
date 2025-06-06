
# 🐔 Crossy Road Clone with Three.js

This project is a simple 3D endless runner game inspired by the popular **Crossy Road**, built with **Three.js**. The player controls a chicken trying to cross roads, rivers, and obstacles without getting hit or falling!

## 🚀 Features

- Real-time 3D graphics using Three.js
- Infinite world generation (new rows appear as you move forward)
- Score tracking
- Smooth keyboard and on-screen controls
- Lightweight and easily extendable architecture

## 🎮 Gameplay

Move the chicken across different terrains while avoiding cars and water. Try to go as far as possible!

| Key      | Action         |
|----------|----------------|
|  ↑       | Move forward   |
|  ↓       | Move backward  |
|  ←       | Move left      |
|  →       | Move right     |

Mobile controls are also available via on-screen directional buttons.

## 🧰 Technologies Used

- [Three.js](https://threejs.org/)
- HTML, CSS, JavaScript


## 📦 Installation

1. Clone the repository:
   
   git clone 


2. Install dependencies (if using a bundler like Parcel):

   ```bash
   npm install
  


3. Start the development server:

   ```bash
   npm run dev
   

4. Open the game in your browser:

   ```
   http://localhost:1234
  

## 🛠️ Development Notes

* The `generateNextRow()` function dynamically creates new terrain rows (grass, roads, rivers, etc.).
* The camera follows the player based on their position.
* The game scene uses a basic Three.js setup with `Scene`, `Camera`, and `Renderer`.


