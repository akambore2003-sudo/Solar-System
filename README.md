# 🪐 Interactive CSS Solar System Simulation

A smooth, visually engaging 2D solar system model built entirely using **HTML5** and **CSS3**. The simulation replicates the orbital motion of all eight planets revolving around a central Sun using CSS Keyframes, with no JavaScript overhead.

---

## 🚀 Key Features

* **Pure CSS Animations:** Leverages `@keyframes` and `transform: rotate()` for high-performance rendering.
* **Proportional Orbit Speeds:** Inner planets complete their years rapidly, while outer planets move at a stately, slower pace.
* **Modern CSS Techniques:** Built using **Flexbox** for layout centering and **absolute positioning** to keep orbits perfectly aligned.
* **Clean, Modular Code:** Orbits act as rotating containers, making it incredibly easy to scale planet sizes, colors, and speeds.

---

## 📊 Planet Orbit & Speed Guide

The simulation uses relative timing to show the progression of orbit speeds from closest to farthest from the Sun:

| Planet | Color | Orbit Diameter | Speed (Animation Duration) |
| :--- | :--- | :--- | :--- |
| **☀️ Sun** | Yellow (with glow) | *Center* | *Stationary* |
| **🔘 Mercury** | Gray | 100px | `6s` |
| **🟠 Venus** | Orange | 150px | `10s` |
| **🔵 Earth** | Blue | 210px | `14s` |
| **🔴 Mars** | Red | 270px | `18s` |
| **🟡 Jupiter**| Goldenrod | 350px | `24s` |
| **🪐 Saturn** | Khaki | 430px | `30s` |
| **🌐 Uranus** | Light Blue | 510px | `36s` |
| **🔵 Neptune**| Dark Blue | 590px | `42s` |

---

## ⚙️ Customization Tips

Want to tweak the simulation? Here is how to easily modify the project:

### 1. Speed Up or Slow Down Orbits
Find the orbit class in `style.css` (e.g., `.earth-orbit`) and adjust the animation duration value:
```css
/* Change 14s to 5s to make Earth orbit super fast! */
.earth-orbit {
    animation: rotate 5s linear infinite;
}
