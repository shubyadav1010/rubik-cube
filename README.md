# 🧩 Rubik's Cube Solver

A comprehensive web application that helps users solve Rubik's Cubes by providing **step-by-step solutions** with **3D visualizations** and **interactive cube manipulation**.

## 🎯 Features

* **Interactive 3D Cube Visualization**
  Real-time 3D rendering of the cube with smooth animations.

* **Step-by-Step Solution**
  Displays detailed algorithms to solve any valid cube configuration.

* **Multiple Input Methods**
  Support for manual face input and visual cube state setting.

* **Reverse Algorithm**
  Shows how to return to the original scrambled state.

* **Modern React Interface**
  Built with React and Vite for optimal performance.

* **Responsive Design**
  Works on both desktop and mobile devices.

---

## 📁 Project Structure

```
Rubiks-Cube-Solver-main/
├── cuber/                 # Main React application
│   ├── src/
│   │   ├── components/
│   │   │   ├── start_page/     # Welcome/landing page
│   │   │   ├── positioning/    # Cube orientation guide
│   │   │   ├── face_set/       # Face color input interface
│   │   │   └── solver/         # Main solving interface
│   │   ├── App.jsx             # Main application component
│   │   └── main.jsx            # Application entry point
│   ├── package.json            # Dependencies and scripts
│   └── vite.config.js          # Vite configuration
├── solver-asset/              # Additional solver assets
│   ├── app/
│   ├── cube/
│   └── color-track-test/
```

---

## 🚀 Getting Started

### Prerequisites

* Node.js (version 14+)
* npm or yarn

### Installation

```bash
git clone https://github.com/your-repo/Rubiks-Cube-Solver-main.git
cd Rubiks-Cube-Solver-main/cuber
npm install
```

### Development Server

```bash
npm run dev
```

Then open your browser at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

---

## 🎮 How to Use

### 1. Start Page

* Welcome screen with introduction
* Click **"Start"** to begin

### 2. Cube Positioning

* Learn cube orientation and naming
* Understand 3D coordinate system

### 3. Face Input

* Input cube colors using:

  * `g` = Green
  * `r` = Red
  * `w` = White
  * `y` = Yellow
  * `o` = Orange
  * `b` = Blue
* Centers are auto-set; follow interface prompts

### 4. Solution

* Step-by-step algorithm display
* Navigate through moves
* 3D animation of cube solving
* View both **solve** and **reverse** steps

---

## 🛠️ Technical Details

### 🧩 Dependencies

* **React 18.2.0** – Frontend framework
* **Vite 4.0.0** – Build tool
* **rubiks-cube-solver 1.2.0** – Core solver logic
* **react-confetti 6.1.0** – Celebration animation

### 🧱 Key Components

* `App.jsx` – App entry & state logic
* `Solver` – Solving logic & 3D visualizer
* `FaceSet` – Color input interface
* `Positioning` – Orientation education

---

## 🧠 Cube Representation

* 26 pieces: corners, edges, and centers
* 6 faces with 9 stickers each
* Accurate orientation and sticker tracking
* Smooth CSS3 animations

---

## 🎨 Features in Detail

### 3D Visualization

* Realistic rendering with shadows
* Smooth move transitions
* Interactive camera

### Algorithm Display

* Move notation: R, U, F, etc.
* Forward and reverse tracking
* Move counter, pause/resume support

### UX & UI

* Clean and intuitive color input
* Visual feedback for interactions
* Mobile-optimized
* Confetti effect on success 🎉

---

## 🔧 Development Scripts

* `npm run dev` – Start dev server
* `npm run build` – Build app
* `npm run preview` – Preview production build

---

## 🧩 Component Architecture

* Modular and reusable React components
* Functional components using hooks
* Scoped CSS modules for styling
* Clear separation of concerns

---

## 🤝 Contributing

1. Fork this repository
2. Create a new branch
3. Commit and test your changes
4. Submit a pull request

---

## 📝 License

This project is open-source and licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

* Built with modern web technologies
* Utilizes `rubiks-cube-solver` for solving logic
* Inspired by the challenge of solving Rubik’s Cubes efficiently

---

**Happy Solving! 🧠🧊**
