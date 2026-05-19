# ⚛️ Quantum Particle in a Box Visualizer

A C-based simulation and visualization project for the **Quantum Mechanical Particle in a 1D Box (Infinite Potential Well)**.

This program allows users to visualize:

- Wavefunctions ψₙ(x)
- Probability Density |ψₙ(x)|²
- Energy Eigenstates

using terminal-based ASCII graphics.

---

## ✨ Features

✅ Visualize Quantum Wavefunctions ψₙ(x)  
✅ Plot Probability Density |ψₙ(x)|²  
✅ Display Energy Eigenstate Levels  
✅ Support for Single and Multiple Quantum Numbers (n)  
✅ ASCII Graphical Representation in Terminal  
✅ Interactive User Input

---

## 🧠 Physics Concept

This project is based on the **Particle in a Box** model in quantum mechanics.

For a particle confined in a one-dimensional box:

\[
\psi_n(x) = \sin\left(\frac{n\pi x}{L}\right)
\]

Where:

- **n** → Quantum number
- **L** → Width of the box
- **ψₙ(x)** → Wavefunction

The probability density is:

\[
|\psi_n(x)|^2
\]

Energy levels follow:

\[
E_n \propto n^2
\]

---

## 🛠️ Tech Stack

- **C Programming**
- **Math Library (`math.h`)**
- Terminal / Console ASCII Graphics

---

## 📂 Project Structure

```txt
Quantum-Particle-In-Box/
│── main.c
│── README.md
```

---

## ⚙️ Compilation

Compile using GCC:

```bash
gcc main.c -o quantum -lm
```

The `-lm` flag is required for the math library.

---

## ▶️ Run the Program

```bash
./quantum
```

For Windows:

```bash
quantum.exe
```

---

## 🎮 Program Options

The program provides three visualization modes:

### 1. Wavefunction Graph (`w`)
Visualizes:

```txt
ψₙ(x)
```

Shows standing wave patterns inside the box.

---

### 2. Energy Eigen Graph (`e`)
Displays quantum energy levels:

```txt
E₁
E₂
E₃
```

Based on:

```txt
E ∝ n²
```

---

### 3. Probability Density Graph (`p`)
Plots:

```txt
|ψₙ(x)|²
```

Shows where the particle is most likely to be found.

---

## 📸 Example Workflow

```txt
Enter width of the box: 20

WHAT DO YOU WANT TO OBSERVE---
1) Wavefunction graph? (type 'w')
2) Energy eigen graph? (type 'e')
3) Probability density graph? (type 'p')

n=? single(type 's') or multiple(type 'm')
```

---

## 🚀 Future Improvements

- Graphical UI version
- Real plotted graphs using OpenGL/SDL
- Quantum tunneling simulation
- Time-dependent wavefunction visualization
- Better graph scaling
- Save graph output to file

---

## 📚 Concepts Used

- Quantum Mechanics
- Infinite Potential Well
- Wavefunctions
- Probability Density
- Energy Quantization
- Mathematical Visualization

---

## 👨‍💻 Author

**Namit**  
Physics & Programming Enthusiast
