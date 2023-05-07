# Do Left-handed People Really Die Young?
## Description
Barack Obama is left-handed. So are Bill Gates and Oprah Winfrey; so were Babe Ruth and Marie Curie. A [1991 study](https://www.nejm.org/doi/full/10.1056/NEJM199104043241418) reported that left-handed people die on average nine years earlier than right-handed people. Nine years! Could this really be true?

In this project, we will explore this phenomenon using age distribution data to see if we can reproduce a difference in average age at death purely from the changing rates of left-handedness over time, refuting the claim of early death for left-handers. This notebook uses `pandas` and Bayesian statistics to analyze the probability of being a certain age at death given that you are reported as left-handed or right-handed.
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with Python kernel support. Make sure to install the required packages such as `pandas`, `numpy`, and `matplotlib`. You can do this by running the following commands in a code cell within the notebook:
```python
!pip install pandas numpy matplotlib 
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the Python kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Ensure you have Python installed. If not, you can download and install Python from the [official Python website](https://www.python.org/downloads/).
## Contents
1. **Where are the old left-handed people?:** Load the handedness data from the National Geographic survey and create a scatter plot.
2. **Rates of left-handedness over time:** Add two new columns, one for birth year and one for mean left-handedness, then plot the mean as a function of birth year.
3. **Applying Bayes' rule:** Create a function that will return P(LH | A) for particular ages of death in a given study year.
4. **When do people normally die?:** Load death distribution data for the United States and plot it.
5. **The overall probability of left-handedness:** Create a function called P_lh() which calculates the overall probability of left-handedness in the population for a given study year.
6. **Putting it all together: dying while left-handed (i):** Write a function to calculate P_A_given_lh().
7. **Putting it all together: dying while left-handed (ii):** Write a function to calculate P_A_given_rh().
8. **Plotting the distributions of conditional probabilities:**
9. **Moment of truth: age of left and right-handers at death:**
10. **Final comments:**