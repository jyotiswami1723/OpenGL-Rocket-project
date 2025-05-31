# 🚀 OpenGL Rocket Launch Project

This project is a simple OpenGL-based animation that simulates a **rocket launch**. It is developed using **OpenGL** and **GLUT** in C++. The animation includes the rocket launching vertically with a visual trail and background.

---

## 🎯 Objective

To demonstrate basic computer graphics concepts using OpenGL:
- Drawing 2D shapes
- Animation with timers
- Using keyboard inputs (optional)
- Simulating real-world motion (rocket launch)

---

## 🛠️ Technologies Used

- **Language:** C++
- **Graphics Library:** OpenGL
- **Utility Toolkit:** GLUT / FreeGLUT
- **Platform:** Windows

---

## 📦 Requirements

Before running the project, make sure the following are installed:

1. **MinGW-w64** (C++ Compiler for Windows)  
   📥 [Download MinGW-w64](https://www.mingw-w64.org/)
   
2. **FreeGLUT Library**  
   📥 [Download FreeGLUT for Windows](http://www.transmissionzero.co.uk/software/freeglut-devel/)

---

## 🧰 Setup Instructions

1. **Install MinGW-w64** and add its `bin` folder to your **System PATH**.
2. **Install FreeGLUT**:
   - Copy `freeglut.dll` to `C:\Windows\System32` and `C:\Windows\SysWOW64`
   - Copy `freeglut.lib` to `C:\MinGW\lib`
   - Copy `GL` folder (with headers) to `C:\MinGW\include\GL`

---

## 🚀 How to Compile and Run

Use this command in the terminal where your `rocket.cpp` is saved:

```bash
g++ rocket.cpp -o rocket.exe -lfreeglut -lopengl32 -lglu32
