# MonteCarlo-Simulation-Loan-Amortization
This Python tutorial is designed to simulate and visualize the potential lifetimes of a loan under various scenarios. It uses a Monte Carlo method to simulate thousands of potential loan payoff trajectories given varying probabilities of making extra payments or late payments.

![Python Version](https://img.shields.io/badge/Python-3.6%2B-blue)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[![Forks](https://img.shields.io/github/forks/Py-Fi-nance/MonteCarlo-Simulation-Loan-Amortization)](https://github.com/Py-Fi-nance/MonteCarlo-Simulation-Loan-Amortization/network)
[![Stars](https://img.shields.io/github/stars/Py-Fi-nance/MonteCarlo-Simulation-Loan-Amortization)](https://github.com/MonteCarlo-Simulation-Loan-Amortization/stargazers)

## Table of Contents

1. [Description](#description)
   - [Loan Parameters Setup](#loan-parameters-setup)
   - [Monte Carlo Parameters Setup](#monte-carlo-parameters-setup)
   - [Monte Carlo Simulation](#monte-carlo-simulation)
   - [Results Visualization](#results-visualization)
   - [Additional Scenarios](#additional-scenarios)
   - [Empirical Rule Calculation](#empirical-rule-calculation)
2. [Requirements](#requirements)
3. [Usage](#usage)
4. [Notes](#notes)
5. [Contributing](#Contributing)

## Description <a name="description"></a>

#### Loan Parameters Setup <a name="loan-parameters-setup"></a>
It starts by defining parameters for a loan, such as the principal amount, annual interest rate, and term in years. These are then used to calculate the monthly payment using a standard loan amortization formula.

#### Monte Carlo Parameters Setup <a name="monte-carlo-parameters-setup"></a>
It then sets parameters for a Monte Carlo simulation, which includes the number of simulations to run and the probability of making extra payments. These extra payments are randomly applied to some months during the loan payoff period.

#### Monte Carlo Simulation <a name="monte-carlo-simulation"></a>
The script runs the Monte Carlo simulation, tracking the loan balance month by month and recording how many payments it takes to fully pay off the loan. Each simulation represents a possible loan lifetime.

#### Results Visualization <a name="results-visualization"></a>
The results are plotted in a histogram, showing the distribution of possible loan lifetimes.

#### Additional Scenarios <a name="additional-scenarios"></a>
The script then runs additional simulations for different probabilities of making extra payments, and for different probabilities of making late payments. The impact of these scenarios on the loan lifetime is visualized in additional histograms.

#### Empirical Rule Calculation <a name="empirical-rule-calculation"></a>
For each scenario, it computes the mean and standard deviation of the loan lifetimes, and reports the intervals within which 68%, 95%, and 99.7% of loan lifetimes fall (according to the empirical rule in statistics).

## Requirements <a name="requirements"></a>
To run this script, you need Python and several packages including numpy, pandas, matplotlib, numpy-financial, and scipy. You can install these packages using pip.

## Usage <a name="usage"></a>
Simply run the Python script to start the simulation and generate the plots. You can adjust the loan parameters and the parameters for the Monte Carlo simulations as needed.

## Notes <a name="notes"></a>
This script assumes that the interest is calculated on a monthly basis. If your loan uses a different compounding period, you will need to adjust the script accordingly. It provides a useful illustration of the potential impact of making extra payments on the speed of loan payoff, as well as the potential consequences of making late payments. For any questions or inquiries, please contact support@pyfi.com - Subject: Github Repo Q, MonteCarlo-Simulation-Loan-Amortization.
For a full article walkthrough please visit > (https://www.pyfi.com/blog/monte-carlo-simulation-python) < where you'll also be able to pick up a complimentary copy of the complete, Volume I text of our Machine Learning Edge Blueprint, a $49 value. This text will walk you through everything you need to get started coding Python for Finance
[![Follow on LinkedIn](https://img.shields.io/badge/Follow%20on-LinkedIn-blue?style=social&logo=linkedin)](https://www.linkedin.com/company/pyfi/)

## Contributing <a name="Contributing"></a>
We welcome contributions to this project. To contribute:

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.
