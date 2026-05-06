# 🧬 Genetic Algorithm for Traveling Salesman Problem (TSP)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Optimization](https://img.shields.io/badge/Optimization-Genetic%20Algorithm-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 🚀 Overview

This project implements a **Genetic Algorithm (GA)** to solve the classic **Traveling Salesman Problem (TSP)** using a set of Colombian cities.

The goal is to determine the **optimal route with the minimum total distance**, visiting each city exactly once and returning to the starting point. The solution is achieved through evolutionary optimization techniques.

---

## 🧠 Key Features

* ✔ Genetic Algorithm implemented from scratch
* ✔ Route optimization across multiple cities
* ✔ Fitness function based on total distance
* ✔ Evolution across generations
* ✔ Visualization of convergence and optimal route

---

## 🧰 Tech Stack

* **Language:** Python
* **Libraries:** NumPy, Matplotlib
* **Concepts:** Genetic Algorithms, Optimization, TSP

---

## 📁 Project Structure

```
genetic-algorithm-tsp/
│
├── notebooks/
│   └── tsp_genetic_algorithm.ipynb
├── images/
│   ├── evolution.png
│   └── ruta_optima.png
├── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/pipediaz1234/genetic-algorithm-tsp.git
cd genetic-algorithm-tsp
```

Install dependencies:

```bash
pip install numpy matplotlib
```

---

## ▶️ Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```
notebooks/tsp_genetic_algorithm.ipynb
```

---

## 🔍 Methodology

The Genetic Algorithm follows these steps:

1. **Initialization:** Generate random routes (initial population)
2. **Evaluation:** Compute total distance (fitness function)
3. **Selection:** Choose best-performing individuals
4. **Crossover:** Combine routes to generate offspring
5. **Mutation:** Introduce diversity
6. **Iteration:** Repeat until convergence

---

## 📊 Results & Visualizations

### 🔹 Evolution of Best Distance per Generation

![Evolution](images/evolution.png)

📌 The algorithm converges around generation **13**, reaching a minimum distance of approximately:

**1807.23 km**

---

### 🔹 Optimal Route (Colombian Cities)

![Optimal Route](images/ruta_optima.png)

📍 Cities included in the route:

* Bogotá (Start/End)
* Cali
* Pereira
* Manizales
* Medellín
* Bucaramanga
* Barranquilla
* Cartagena

---

## 📈 Performance Analysis

* Fast convergence in early generations
* Stable solution after generation 13
* Efficient reduction of total travel distance

---

## 💡 Future Improvements

* 🔹 Increase population size
* 🔹 Advanced crossover strategies
* 🔹 Hybrid optimization (GA + Local Search)
* 🔹 Interactive visualization

---

## 👨‍💻 Author

**Andrés Felipe Díaz Campos**
Systems Engineering Student | Backend & AI Developer

🔗 LinkedIn:
https://www.linkedin.com/in/andres-felipe-diaz-campos-398245207/

---

## 📄 License

This project is intended for academic and portfolio purposes.
