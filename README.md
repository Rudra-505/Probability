
# Probability and Statistics Simulations in Python

This project contains a collection of small Python simulations and visualizations for basic probability and statistics concepts using random experiments and NumPy/Matplotlib.

## Contents

The notebook includes code for:

1. **Coin toss and dice roll simulation**  
   - Toss a fair coin 10,000 times to estimate the probability of heads and tails.  
   - Roll two dice multiple times and estimate the probability of getting a sum of 7.

2. **Probability of getting at least one 6**  
   - Repeatedly roll a fair die 10 times in each trial.  
   - Estimate the probability of getting at least one “6” using simulation.

3. **Bayes’ theorem with colored balls**  
   - Simulate drawing balls from a bag with red, green, and blue balls (with replacement).  
   - Estimate \(P(\text{Red} \mid \text{Previous was Blue})\) and compare it with Bayes’ theorem using empirical frequencies.

4. **Discrete random variable sampling**  
   - Generate 1000 samples from a discrete random variable with given probabilities for X = 1, 2, 3.  
   - Compute empirical mean, variance, and standard deviation.

5. **Exponential distribution simulation**  
   - Generate 2000 samples from an exponential distribution with a given mean.  
   - Visualize the distribution using a histogram and an overlaid probability density function (PDF).

6. **Central Limit Theorem (CLT) demonstration**  
   - Create a population from a uniform distribution on.
   - Draw many samples of fixed size and plot the distribution of sample means to illustrate the CLT.

## Requirements

- Python 3.x  
- `numpy`  
- `matplotlib`  
- `jupyter` (if you want to run the notebook interactively)

Install the required packages with:

```bash
pip install numpy matplotlib jupyter
```

## How to Run

1. Clone this repository or download the notebook/file.  
2. Start Jupyter Notebook or JupyterLab in the project directory:  
   ```bash
   jupyter notebook
   ```
3. Open the notebook and run the cells in order to see the simulations and plots.

## Learning Objectives

- Understand experimental/empirical probability through simulation.  
- Visualize distributions and summary statistics.  
- Observe conditional probability and Bayes’ theorem in action.  
- See the Central Limit Theorem via sampling from a population.
