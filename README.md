# Data Collection on Emails Received per Day (Poisson Distribution)

![Poisson Distribution](https://img.shields.io/badge/Python-3.8%2B-blue) ![License](https://img.shields.io/badge/License-MIT-green) ![Status](https://img.shields.io/badge/Status-Completed-success)

## Overview

This project models the daily email reception counts for three individuals using the Poisson distribution. It involves data collection in a structured format, computation of the average rate parameter (λ), and visualization of the Poisson probability mass function. The analysis serves as an educational demonstration of applying statistical distributions to real-world count data, such as email traffic.

## Problem Statement

In professional and personal settings, the volume of emails received daily can exhibit variability that follows a Poisson distribution, making it essential to model such patterns for effective time management, server optimization, and predictive analytics. This project collects data on the number of emails received by three individuals over a seven-day period, calculates the average rate parameter (λ), and applies the Poisson distribution to estimate the probability of observing a specific number of emails on any given day. By addressing the discrete and random nature of email arrivals, the analysis provides insights into communication trends while demonstrating statistical modeling techniques for count-based data.

## Dataset

- **Source**: The dataset is hardcoded in the notebook as a dictionary representing email counts for three persons (A, B, C) across seven days (Monday to Sunday).
- **Size**: 21 entries (3 persons × 7 days).
- **Key Features**:
  - Categorical: Person (A, B, C), Day of the Week.
  - Numerical: Email Counts (integers ranging from 7 to 14 in the provided data).
- **Preprocessing Steps**:
  - Flatten the dictionary into a list of counts.
  - Compute the mean (λ) for the Poisson distribution.

No external file is required; data is defined within the code.

## Technologies Used

- **Programming Language**: Python 3.12+
- **Libraries**:
  - Numerical Computing: `numpy`
  - Visualization: `matplotlib`
  - Statistics: `scipy.stats` (for Poisson PMF)
- **Environment**: Jupyter Notebook
