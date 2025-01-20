# **Mod1-Intro-to-Jupyter-and-R**  
**Statistical Inference and Hypothesis Testing in Data Science Applications**

Author: Sulay Cay 

Inspired By: University Of Colorado Boulder

Date: 2025-Jan-20


## **Overview**  
This repository contains coursework and solutions related to **Statistical Inference and Hypothesis Testing in Data Science Applications**, using the **R programming language** in Jupyter Notebook. The focus is on understanding fundamental concepts such as hypothesis testing, probability distributions, and statistical inference with real-world data applications.

---

## **Contents**  

### **1. Introduction to Jupyter and R**  
This section covers the basics of using R within Jupyter Notebooks, including:

- Setting up the environment
- Writing R code in Jupyter cells
- Markdown for documentation and LaTeX for equations
- Basic R operations such as vectors, sequences, and functions
- Exploratory data analysis with visualization

### **2. Hypothesis Testing Concepts**  
In this module, we delve into hypothesis testing, focusing on the following topics:

- **Null and Alternative Hypotheses:**
  - Defining hypotheses for experiments
  - Choosing the appropriate statistical test
- **Type I and Type II Errors:**
  - Understanding false positives and false negatives
  - Evaluating the consequences of each error
- **Significance Levels (α):**
  - Choosing the right level of significance
  - Critical value interpretation
- **One-tailed and Two-tailed Tests:**
  - Comparing experimental outcomes with critical values

### **3. Statistical Distributions and Calculations in R**  
Key statistical functions explored in this module:

- **Normal Distribution:**
  - Using `pnorm()` to calculate cumulative probabilities
  - Using `qnorm()` to find quantiles (inverse CDF)
  - Standardization of random variables for hypothesis testing
- **Simulation and Visualization:**
  - Generating random samples with `rnorm()`
  - Plotting density histograms using `hist()` and `dnorm()`
- **Central Limit Theorem (CLT):**
  - Sample mean distribution and standard error calculation

### **4. Practical Applications and Case Studies**  
This section includes problem-solving exercises, such as:

- **Psychic Abilities Testing with Coin Flips:**  
  - Formulating hypotheses to test claims of superhuman predictive abilities  
  - Computing probabilities and errors associated with decision-making  
  - Matching hypothesis results to real-world outcomes

- **Analysis of Equine Anesthetic Effects:**  
  - Testing lateral recumbency time using normal distribution  
  - Applying statistical significance testing to clinical data

- **Birdwatching Hypothesis Test:**  
  - Using sample data to validate claims about species observations  
  - Performing hypothesis tests and interpreting results

---

## **Key R Functions Used**  
Here are some important R functions utilized in the coursework:

| Function       | Purpose                                      |
|----------------|----------------------------------------------|
| `pnorm()`       | Calculates cumulative probability (CDF)     |
| `qnorm()`       | Computes quantiles (inverse CDF)            |
| `rnorm()`       | Generates random normal samples             |
| `dnorm()`       | Evaluates the probability density function  |
| `mean()`        | Computes the mean of a vector               |
| `var()`         | Computes the variance                       |
| `hist()`        | Generates a histogram plot                  |
| `table()`       | Frequency count of categorical values       |

---

## **Project Structure**  

```
Mod1-Intro-to-Jupyter-and-R/
│-- README.md                 # Documentation of the project
│-- Mod1_autograded.ipynb      # Jupyter Notebook with code and answers
│-- data/                      # Data files used for the assignments (if applicable)
│-- figures/                   # Plots and images generated during analysis
└-- scripts/                   # R scripts for various statistical tests
```

---

## **How to Run the Project**  

### **Prerequisites:**  
Ensure you have the following installed:

1. **Jupyter Notebook** (with R kernel)  
2. **R programming language** (version 4.0 or above)  
3. R libraries required:  
   ```r
   install.packages(c("testthat"))
   ```

### **Steps to Run:**  

1. Clone the repository:

   ```bash
   git clone https://github.com/sulay01/Mod1-Intro-to-Jupyter-and-R.git
   cd Mod1-Intro-to-Jupyter-and-R
   ```

2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open `Mod1_autograded.ipynb` and run the cells sequentially.

---

## **Results and Insights**  
Throughout the assignments, we have analyzed statistical scenarios and validated hypotheses using data-driven approaches. Some key insights include:

- Understanding when to reject or fail to reject a null hypothesis.
- The importance of proper significance levels to minimize Type I and Type II errors.
- Simulating real-world scenarios such as product quality control and medical testing.

---

## **Future Work and Improvements**  
Some potential areas for further exploration:

- Implementing hypothesis testing on larger datasets.
- Applying statistical inference to machine learning models.
- Exploring Bayesian inference methods alongside frequentist approaches.

---

## **Acknowledgments**  
Special thanks to the instructors and peers for their support throughout this module. Resources such as R documentation and statistical textbooks were instrumental in completing the assignments.

---

## **Contact**  
For any questions or collaborations, feel free to reach out:

- **GitHub:** [Sulay Cay](https://github.com/sulay01)  
- **LinkedIn:** [Sulay Cay](https://www.linkedin.com/in/sulay-cay-0589513a)

---

