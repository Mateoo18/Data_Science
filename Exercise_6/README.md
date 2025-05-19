# Assignment 6 – Statistical Inference: Confidence Intervals and Sampling Distributions

This notebook explores the core concepts of **statistical inference**, focusing on confidence intervals, sampling variability, and the standard error of the mean (SEM). It uses real-world housing data from King County, Washington (USA) to simulate population vs. sample-based reasoning.

## 📊 Dataset

- **King County Housing Dataset**  
- Covers **21,613 home sales** between May 2014 and May 2015  
- Contains features such as house prices, square footage, location, and more  
- Treated as a full population for sampling simulations

## 📌 Contents

### 🧪 Exercise 1: Sampling and Variability

- Randomly draw a sample of 100 house prices from the population
- Compare:
  - Histograms
  - Means and standard deviations of population vs. sample
- Observe how these statistics change with repeated sampling

### 🔁 Exercise 1b: Sampling Distributions

- Generate 1000 samples of size N=100  
- Compute sample mean for each sample  
- Plot the sampling distribution of means  
- Compare to the true population mean

### 📉 Exercise 1c: Standard Error vs. Sample Size

- Draw samples with sizes N=2, 4, 8, ..., 4096  
- Compute standard deviation of sample means  
- Plot against theoretical $1/\sqrt{N}$  
- Visualize the relationship on a log-log scale

## 🧠 Key Concepts Illustrated

- Confidence intervals
- Sampling distribution of the mean
- Law of Large Numbers
- Central Limit Theorem
- Standard error and its dependence on sample size

## 🛠️ Tools & Libraries

- Python
- numpy
- pandas
- matplotlib

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Mateoo18/Data_Science.git
   cd Data_Science/Exercise_6
