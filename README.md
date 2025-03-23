# 🎥 Ballerina Static Canvas Animation

This project demonstrates a creative canvas animation using HTML5 `<canvas>` and a video element. The animation displays a video on the canvas and applies a unique static effect by preserving old frames and applying a black-and-white noise effect where the new frame pixels are black.

---
## 🎬 Preview

![Canvas Animation Preview](/Preview.mp4)

---

## 🚀 Features

- Renders video onto a canvas.
- Applies a unique glitch/static effect by comparing video frames.
- Click-to-pause/play functionality on canvas.
- Pure HTML5 + JavaScript, no external libraries required.

---

## 📂 Project Structure

project-root/ │ 
├── index.html # Main HTML file containing all code
├── vid.mp4 # Video file used for animation (place in same folder)
└── README.md # Documentation (this file)


---

## 📸 How It Works

1. The video is loaded and played in the background.
2. Each frame is drawn on the canvas using `drawImage()`.
3. A pixel comparison is done:
   - If a pixel in the current frame is black (`r == 0`), a random black or white pixel is drawn.
   - Otherwise, it uses the previous frame’s pixel value to create a "memory effect".

---

## 🖱 Controls

- **Click on the canvas** to toggle **Play/Pause** of the video and animation.

---

## 📦 How to Use

1. Clone or download this repository.
2. Replace `vid.mp4` with your own video file (ensure it’s in the same directory).
3. Open `index.html` in any modern browser.
4. Click on the canvas to interact.

---

## 🔧 Requirements

- A modern web browser (Chrome, Firefox, Edge, etc.)
- A video file named `vid.mp4` in the same directory.

---

## 📌 Notes

- The video will play muted and loop automatically.
- If you'd like to control sound, set `video.muted = false` in the script.
- If your video dimensions differ, adjust the `<canvas>` width and height as needed.

---

## 📄 License

This project is open-source and free to use for personal and educational purposes.

---

## ✍️ Author

**Krishnendu Halder**  
Feel free to reach out for collaboration or feedback!

📧 Email: krishnendu.work@gmail.com
