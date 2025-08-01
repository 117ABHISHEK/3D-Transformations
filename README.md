
# 🧊 3D Transformations in C++ using BGI Graphic

This project demonstrates **basic 3D transformation operations** — **Translation**, **Scaling**, and **Rotation** — on a simple object (a bar/rectangle) using the **<graphics.h>** BGI library in C++.

## 📌 Overview

The code visually performs:
- **Translation** – Moves the object to a new location.
- **Scaling** – Resizes the object based on scale factors.
- **Rotation** – Rotates the object by a given angle.

Although the concept is 3D, the visual demonstration here is 2D with transformation logic inspired by 3D math (especially rotation).

## 🧪 What’s Inside

- `Translation(tx, ty)` – Moves the shape by `(tx, ty)` units.
- `Scaling(Sx, Sy, Sz)` – Scales the shape with given scale factors.
- `Rotation(theta)` – Rotates the shape using 2D rotation logic (around Z-axis equivalent).

Each transformation:
- Draws the **original shape** first.
- Then applies the transformation.
- Draws the **transformed shape** in a different color.
- Displays console messages for verification.

## 🎨 Output Preview

The program uses:
- 💚 **Green** for translation
- 🔴 **Red** for scaling
- 🟡 **Yellow** for rotation

All drawn using the **`bar()`** function to represent the rectangle object.

## 🔧 Requirements

- Turbo C++ / Dev-C++ with BGI support  
- BGI graphics driver (use Turbo C++ or set up `graphics.h` in modern compilers manually)
- Compatible with Windows systems using DOSBox or native graphics support

## 🚀 How to Run

1. Ensure your environment supports `<graphics.h>`.
2. Compile and run the C++ file.
3. A graphics window will open and show each transformation one after another.
4. Press any key to exit after viewing.

## 📌 Sample Usage

```cpp
Translation(100, 50);          // Moves the shape
Scaling(1.5f, 1.5f, 1.0f);     // Scales the shape
Rotation(45);                  // Rotates the shape by 45 degrees
```

## 📚 Concepts Covered

- 2D/3D Transformation Basics
- Coordinate System in Graphics
- Rotation using Trigonometry
- Matrix-based transformation logic (implied)
- Console + Visual Output integration

## 📁 File Structure

```
3D-Transformations/
│
├── transformations.cpp   # Main source file
├── README.md             # You're here
```

## 🧠 Note

- The code simulates **3D-like** transformations but visual output is in 2D.
- True 3D transformations would involve Z-axis projection which is not shown visually here.

## 👨‍💻 Author

**Abhishek**

Built by a developer learning the core principles of computer graphics through code.
