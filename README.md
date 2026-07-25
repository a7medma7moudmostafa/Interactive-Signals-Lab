
# ⚡ SignalsLab Workspace

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Engineering](https://img.shields.io/badge/Field-Electrical%20Engineering-orange.svg)

## 📖 About The Project

**SignalsLab Workspace** is an interactive Signal Processing Simulator designed to bridge the gap between theoretical mathematics and practical engineering applications. Built specifically for Electrical Engineering students and professionals, it provides a real-time visual environment to explore continuous and discrete signals without the need for complex desktop software. 

The core motivation behind this project was to transform abstract theoretical formulas into intuitive, visual, and dynamic tools.

## ✨ Key Features

- **🧮 Custom Equation Engine:** Input any mathematical signal equation (e.g., `sin(2*pi*t) * exp(-t)`) and watch it render instantly.
- **⏳ Time-Domain Transformations:** Apply real-time Time Shifting, Time Scaling, and Time Reversal through an interactive UI.
- **📡 Two-Signal Operations:** Simulate AM Modulation (Multiplication) and Signal Interference/Noise (Addition).
- **🎬 Animated Convolution:** A step-by-step visual animator for Discrete Convolution demonstrating the mathematical "Flip & Slide" concept dynamically.
- **🎨 Engineering Themes:** Seamlessly toggle between a dark IDE mode (inspired by MATLAB Workspace) and a clean light mode (inspired by Simulink).

## 🛠️ Built With

- **React.js** - Main Frontend Framework
- **Math.js** - Advanced mathematical expression parser and evaluator
- **Recharts** - Responsive charting and data visualization

## 🚀 Getting Started (Local Development)

To run the project locally on your machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone [https://github.com/YourUsername/SignalsLab.git](https://github.com/YourUsername/SignalsLab.git)

```

2. Navigate to the project directory:
```bash
cd SignalsLab

```


3. Install NPM packages:
```bash
npm install

```


4. Start the development server:
```bash
npm run dev

```



## 🌐 Deployment (Manual GitHub Pages Workflow)

This project is deployed using a manual build process. To push updates to the live site, follow this workflow:

1. Make your desired code changes within the `src` directory.
2. Build the production-ready files:
```bash
npm run build

```


3. Navigate to your GitHub repository in the browser.
4. Click **Add file** > **Upload files**.
5. Drag and drop all the contents **inside** the newly generated `dist` folder directly into the repository, overwriting the old files.
6. Click **Commit changes**.
7. Perform a hard refresh (`Ctrl + F5`) on the live GitHub Pages URL to view the updates.

## 🗺️ Roadmap (Version 2 Ideas)

* [ ] Implement Frequency Domain Analysis (Fast Fourier Transform).
* [ ] Add `.wav` audio file support for real-time digital filtering.
* [ ] Z-Transform & Pole-Zero map visualization.

## 👨‍💻 Developer

**Ahmad**
*Electrical Engineering Student (Communications Major)*

* **Email:** ahmedaboabbas1@gmail.com
* **WhatsApp:** [+201093358794](https://www.google.com/search?q=https://wa.me/201093358794)
* **LinkedIn:** [Ahmad's LinkedIn](https://linkedin.com/in/yourprofile)
