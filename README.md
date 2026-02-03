---

# Heart Curve Turtle Visualization

This project is a Python program that uses 
**mathematics and turtle graphics** 
to render a stylized heart shape. 
The heart is generated using parametric equations 
and drawn with radial strokes to create a dynamic, 
artistic visual effect.

---

## ❤️ Project Purpose

The goal of this project is to:

* Demonstrate the use of **parametric equations** in visual form
* Apply **trigonometric functions** (`sin`, `cos`) to generate complex curves
* Showcase Python’s built-in **turtle graphics** module for creative coding
* Combine math and graphics to produce an aesthetically pleasing animation

Instead of drawing a continuous outline, 
the program draws thousands of strokes radiating from the center, 
creating a glowing, textured heart effect.

---

## 🧮 How It Works

* The heart shape is defined using parametric equations:

  * `x(k) = 15 sin³(k)`
  * `y(k) = 12 cos(k) − 5 cos(2k) − 2 cos(3k) − cos(4k)`
* The parameter `k` is incremented gradually to ensure smoothness
* Each iteration draws a line from the center of the screen to a point on the heart curve
* Turtle settings are optimized for speed and visual clarity

---

## 🛠️ Technologies Used

* **Python 3**
* Standard Library Modules:

  * `math`
  * `turtle`

No third-party libraries are required.

---

## 🚀 How to Run the Program (Terminal)

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/heart-curve-turtle.git
```

### 2. Navigate to the Project Directory

```bash
cd heart-curve-turtle
```

### 3. Run the Script

```bash
python heart.py
```

> If your system uses `python3`, run:

```bash
python3 heart.py
```

A new window will open and the heart will be drawn automatically.

---

## 📂 Project Structure

```text
heart-curve-turtle/
│
├── heart.py
└── README.md
```

---

## 🎨 Visual Details

* Background: Black
* Stroke color: Deep red
* Stroke style: Radial lines from center
* Drawing speed: Maximum (optimized for smooth rendering)

---

## 🔧 Possible Enhancements

* Animate color transitions
* Add pulsing or heartbeat effects
* Allow user-defined scale or stroke density
* Save the final image to a file

---

## 👤 Duncan Doyon

Created as a mathematical visualization project 
exploring the intersection of **art, geometry, and Python 

