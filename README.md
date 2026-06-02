# 🎡 Wheel of Probability

[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 🎯 Overview

**Wheel of Probability** is a lightweight interactive probability wheel built with pure HTML, CSS, and JavaScript. It lets you create weighted options, spin a colorful wheel, and instantly display a weighted random result.

This project is ideal for decision making, game design, classroom activities, raffles, or any scenario where you want a visually engaging weighted random picker.

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🎡 **Animated Spin** | Smooth wheel animation with easing and finish detection |
| ⚖️ **Weighted Options** | Each option has a `weight` that controls its probability |
| 🧩 **Dynamic Editor** | Add, edit, and delete options on the fly |
| 📊 **Probability Visuals** | Option slices are drawn proportionally on the wheel |
| 🎵 **Sound Feedback** | Tick sound plays while the wheel spins |
| 📱 **Responsive UI** | Works on desktop and smaller screens |
| 🧠 **Single File App** | No dependencies or build tools required |

## 🚀 How to Use

1. Open `roda.html` in a modern browser.
2. Edit the option labels and weights in the "Options" panel.
3. Click the **GIRAR** button to spin the wheel.
4. The selected option appears under the result section.

## 🧠 How It Works

- The wheel draws segments on a Canvas element using each item's relative weight.
- The spin animation rotates the wheel with an ease-out effect.
- The pointer stays fixed while the wheel turns, and the selected segment is computed when the spin ends.
- Weights are normalized so every option has at least a value of `1`.

## 📁 Project Structure

```
wheel of probability/
├── roda.html      # Single-page interactive probability wheel
├── README.md      # Project documentation
└── LICENSE        # Optional license file
```

## 🛠️ Requirements

- A modern browser with Canvas and JavaScript support
- No server or installation required

## 📌 Notes

- Minimum of two options is required to spin the wheel.
- The wheel automatically re-renders after every change.
- The editor shows each option's weight percentage in real time.

## 🤝 Contributing

This is a simple standalone demo, but contributions or improvements are welcome. Feel free to add features like export options, custom themes, or sound controls.

## 📝 License

This project can be used under the **MIT License**. See the `LICENSE` file for details.
