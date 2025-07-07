## Ruin Probability Simulator for Insurance Solvency
An interactive tool for estimating insurer ruin probability using Monte Carlo simulation and a generalized jump-diffusion risk model.

About The Project
Assessing financial solvency is a critical task for insurance companies, and the probability of ruin is a key metric for risk management. This project features a computational tool built to estimate both finite-time, 
ψ(u;τ), and ultimate ruin probability, ψ(u).

The simulator is built on a Monte Carlo engine and uses a generalized jump-diffusion risk model, which incorporates stochastic income from investment returns and premiums against stochastic outflows from claims. The entire tool is packaged in an interactive web application using the Streamlit framework, making it a flexible platform for actuaries and risk managers to analyze solvency and support strategic capital management decisions.

## Key Features
Advanced Risk Modeling: Implements a generalized jump-diffusion model, which is more realistic than classic models as it includes returns on surplus.

Monte Carlo Simulation: Uses a robust simulation engine to estimate probabilities by modeling thousands of potential future scenarios.

Interactive Interface: Allows users to dynamically change parameters and instantly see their impact on solvency risk.

Dual Time Horizon: Capable of estimating both short-term (finite-time) and long-term (ultimate) ruin probabilities.

## Technology Stack
Core Logic: Python

Web Framework: Streamlit

Numerical & Stochastic Calculations: NumPy, SciPy

Data Handling: Pandas

Results from a Case Study
Analysis of a representative case study demonstrated the tool's capability to quantify risk. Under a specific set of assumptions, the model yielded an estimated finite-time ruin probability of 1.15% over a 50-year horizon.

(You can replace the placeholder link above with a real image of a chart from your analysis)

## How To Run Locally
To get a local copy up and running, follow these simple steps.

Prerequisites
You need to have Python 3.8+ and pip installed on your system.

Installation & Execution
Clone the repository:

Bash

git clone https://github.com/ArinaAsaei/your-repository-name.git
cd your-repository-name
Install the required packages:
(First, make sure you have a requirements.txt file in your repository)

Bash

pip install -r requirements.txt
Run the Streamlit app:

Bash

streamlit run app.py
The application should now be open and running in your web browser.

## Further Reading

For a deeper dive into the mathematical model, methodology, and detailed analysis, please refer to the full project report.

[**Read the Full Technical Report**](https://docs.google.com/document/d/1T4bwsijVyeunCSnKChLn2qN6AErdtEDieC9OdYlxZWw/edit?usp=sharing)

## Live Demo in Google Colab

You can run a live, interactive demo of this application directly in your browser using Google Colab, without any local installation.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mCruVeHAqhcoOOKO8OAKdWAp4Rdt2ZHI)