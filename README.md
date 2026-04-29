# Quantitative & Statistical Simulations (Python)
# 🪙 Coin Flip & Monte Carlo Pi Simulation

This project explores how we can estimate the mathematical constant **π (Pi)** using randomness. It includes two primary methods: a standard Monte Carlo simulation and a unique coin-flip probability model.

## 🚀 How it Works

### 1. The "Darts" Method (Standard Monte Carlo)
We simulate throwing random "darts" at a 2x2 square containing a circle with a radius of 1.
* **Area of Square:** 4
* **Area of Circle:** π
* **Ratio:** π / 4

By counting how many random points land inside the circle versus the total points thrown, we can approximate π:
**π ≈ 4 × (Points inside Circle / Total Points)**

### 2. The Coin Flip Method
Based on a method described by mathematician James Propp, we can also estimate π using simple coin tosses. By flipping a coin until the number of heads exceeds the number of tails and recording those fractions, the average of many trials eventually converges to **π/4**.

## 🛠️ Features
- **Visualisation:** Uses [Matplotlib](https://matplotlib.org) to plot points and show the circle's boundary.
- **Accuracy Tracking:** Compares the simulation result against the true value of π (3.14159...).
- **Scalable Iterations:** Change the number of simulations (N) to see how accuracy improves with more data.

## 📦 Requirements
- Python 3.x
- NumPy (for fast random generation)
- Matplotlib (for the cool plots)

## 🏃 Run the Project
1. Clone this repo: `git clone <your-repo-link>`
2. Install dependencies: `pip install numpy matplotlib`
3. Run the script: `python simulate_pi.py`

## 📊 Sample Output
- **Simulations:** 5000
- **Estimated Pi:** 3.1412
- **Error:** 0.0039
