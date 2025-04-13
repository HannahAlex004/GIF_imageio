# GIF Creator using `imageio`

This project demonstrates how to create an animated GIF using a sequence of images with the `imageio` library in Python.

## 🛠️ Requirements

- Python 3.x
- `imageio` library

You can install the required library using:
```bash
pip install imageio
```
## 🧠 How it Works
Reads the images listed in the images array
Combines them into a GIF using imageio.mimsave
Outputs a file named team.gif

## ▶️ How to Run
Run the script in your terminal or command prompt:
```bash
python create_gif.py
```

## 📦 Output
The code will create an animated GIF named team.gif using the provided PNG images.
duration=500 sets the display time of each frame to 500 milliseconds.
loop=0 makes the animation loop infinitely.

## 🔁 Customization
Change the duration to control the frame speed (in milliseconds)
Add or remove images by modifying the images list

Made with ❤️ using Python.