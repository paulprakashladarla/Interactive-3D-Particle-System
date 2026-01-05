# Interactive 3D Particle System with Hand Tracking

A real-time, interactive web application that combines 3D particle physics with computer vision. This project uses **Three.js** for rendering a high-performance particle system and **MediaPipe Hands** for tracking hand gestures via the webcam to interact with the visual elements.

## 🌟 Features

-   **Interactive Particle System**: A 4000-particle cloud that morphs into different 3D shapes.
-   **Hand Gesture Control**:
    -   **Open Hand**: Expands the particle formation.
    -   **Closed Hand (Pinch)**: Contracts/implodes the particles towards the center.
    -   **Real-time Tracking**: Powered by MediaPipe's robust machine learning model.
-   **Shape Templates**:
    -   ❤️ **Hearts**: A parametric 3D heart shape.
    -   🌸 **Flower**: Procedurally generated 3D rose curves.
    -   🪐 **Saturn**: A planet sphere with an orbiting particle ring.
    -   🧘 **Buddha**: A meditative silhouette point cloud.
    -   🎆 **Fireworks**: A volumetric radial burst.
    -   ⚪ **Sphere**: The default uniform distribution.
-   **Live Customization**:
    -   **Color Picker**: Change the particle color theme instantly.
    -   **Modern UI**: Glassmorphism-style control panel overlaid on the canvas.
-   **Single File Deployment**: The entire application (HTML, CSS, JS) is contained within a single `index.html` file for portability.

## 🚀 How to Run

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/paulprakashladarla/Interactive-3D-Particle-System.git
    cd Interactive-3D-Particle-System
    ```

2.  **Serve the file**:
    Due to browser security restrictions on webcam access, you cannot simply double-click `index.html`. You must serve it via a local web server (http vs file protocol).

    **Using Python (Pre-installed on macOS/Linux):**
    ```bash
    # Python 3
    python3 -m http.server 8000
    ```

3.  **Open in Browser**:
    Navigate to `http://localhost:8000` in your web browser (Chrome or Safari recommended).

4.  **Allow Camera Access**:
    When prompted, allow the browser to access your webcam to enable hand tracking.

## 🛠️ Tech Stack

-   **Three.js**: WebGL rendering engine.
-   **MediaPipe Hands**: ML solution for high-fidelity hand and finger tracking.
-   **Vanilla JavaScript**: No bundlers (Webpack/Vite) or complex build steps required.
-   **HTML5/CSS3**: Clean, semantic markup and modern styling.

## 🎮 Controls

-   **Switch Shapes**: Click the buttons in the top-left panel.
-   **Change Color**: Use the color picker to set the mood.
-   **Interact**:
    -   Show your hand to the camera to take control.
    -   Move your hand closer/further to see subtle effects (depending on lighting).
    -   Pinch your fingers to shrink the shape, open your hand wide to expand it.

## 📄 License

This project is open source and available for personal and educational use.