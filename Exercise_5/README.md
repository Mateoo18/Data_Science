# Assignment 5 – Statistical Distributions and Law of Large Numbers

This notebook demonstrates how to work with standard probability distributions using Python and `scipy.stats`. It also illustrates important statistical concepts such as the **Law of Large Numbers (LLN)** and the **Central Limit Theorem (CLT)** through visual simulations.

## 📌 Contents

### 📈 Exercise 1: Sampling from Distributions

- **Normal distribution** with μ=1 and σ=4  
- **Exponential distribution** with λ=1/4  
- **Chi-squared distribution** with 8 degrees of freedom  
- **Uniform distribution** over the interval [−2√3, 6√3]

For each distribution:
- Draw 1000 random samples
- Plot the histogram and theoretical PDF
- Compute and compare theoretical vs sample mean and variance

### 🔁 Exercise 2: Law of Large Numbers (LLN) and Central Limit Theorem (CLT)

- For `N` from 2 to 1000, draw N samples from each distribution
- Plot how sample **mean** and **variance** evolve as N increases
- Visualize convergence to theoretical values
- Show Gaussian-like shape emerging from means of repeated samples

## 📊 Key Concepts Illustrated

- Distribution fitting and parameter estimation
- Comparison of theoretical vs empirical statistics
- LLN: Convergence of sample statistics to population values
- CLT: Normality of sample means as N increases, even from non-normal distributions

## 🧠 Techniques Used

- Sampling using `scipy.stats`
- Calculation of descriptive statistics (mean, variance)
- Visualization of PDFs and histograms
- Convergence plots for LLN and CLT

## 🛠️ Tools & Libraries

- Python
- numpy
- scipy
- matplotlib

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Mateoo18/Data_Science.git
   cd Data_Science/Exercise_5
