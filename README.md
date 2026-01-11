# Monte Carlo Queue Analysis

## Overview
This project uses Monte Carlo simulation to analyze a stochastic queueing system.
Arrival and service processes are inferred from data, and system performance is
evaluated under different staffing policies.

The objective is to quantify both average and tail waiting times and determine
the optimal number of servers by balancing service capacity costs against waiting
penalties.

---

## Problem Statement
Service systems often exhibit low average waiting times while still exposing
customers to significant tail delays under congestion. This project investigates:

- How waiting time distributions behave under stochastic arrivals and services
- How performance changes as the number of servers increases
- Which staffing policy minimizes total expected cost

---

## Methodology
- Generated and analyzed arrival and service time data
- Fitted exponential distributions to model stochastic processes
- Simulated queue dynamics using Monte Carlo methods
- Evaluated single- and multi-server configurations
- Introduced a cost–performance model to identify the optimal staffing level

---

## Key Results
- Single-server systems exhibit low median wait times but significant tail risk
- Adding a second server dramatically reduces both mean and high-percentile waits
- A third server provides diminishing marginal improvement
- Cost–performance analysis identifies the two-server configuration as optimal

---

## Technologies Used
- Python
- NumPy
- Pandas
- SciPy
- Matplotlib
- Jupyter / Google Colab

---

## Conclusion
Monte Carlo simulation provides a flexible framework for evaluating stochastic
service systems. By combining statistical modeling, simulation, and cost analysis,
this project demonstrates how data-driven decisions can optimize operational
performance under uncertainty.
