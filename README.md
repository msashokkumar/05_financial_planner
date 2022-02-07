# Financial Planner for Emergencies and Retirement

This jupyter notebook aimes to provide:

- A financial planner for emergencies: The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

- A financial planner for retirement: This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

## Technologies

This financial planner is a Jupyter notebook built with the following technologies:

### Language

| Language | Version |
|----------|---------|
| Python   | 3.7.11  |

### Libraries and Frameworks

| Component | Version |
|-----------|---------|
| Anaconda  | 1.9.0   |
| Conda     | 4.11.0  |
| Jupyter   | 3.2.1   |

### Operating System

This version of the software is operating system agnostic.

---
## Installation Guide

### Pre-requisites

- Python 3.7
- Anaconda 1.9.0
- Conda 4.11.0
- Jupyter 3.2.1
- A conda environment created specially for this project.
- MCForecastTools.py which provides tools for Monte Carlo simulation.

### Installation

Install a new conda environment for this project. We will be using `python 3.7.11` for this repository.

```bash
conda create -n dev_finplanner python=3.7.11 anaconda
```

Activate the newly created environment and verify the python version.

```bash
conda activate dev_finplanner
python --version
```

Install and add the ipykernel environment to your jupyter notebook.
```bash
conda install -c anaconda ipykernel
python -m ipykernel install --user --name=dev_finplanner
```

Clone the remote repository to your local developer environment and `cd` into the folder.
```bash
git clone git@github.com:msashokkumar/05_financial_planner.git
cd 05_financial_planner
```

Start the jupyter lab server from the terminal as follows:

```bash
jupyter lab
```

Once started successfully, the terminal will look like below and a browser will open automatically.

![Jupyter Lab Started](/Images/01_start_jupyter_labs.png?raw=true "Start jupyter labs server from terminal.")

The jupyter homepage will look like as follows:

![Jupyter Lab Homepage](/Images/02_jupyter_labs_homepage.png?raw=true "Jupyter homepage.")

From the file browser on the left side, open risk_return_analysis.ipynb.

---
## Contributors

```markdown
{
  "name": "Ashok Kumar Madhavi Selvaraj",
  "email": "ashok.ms.kumar@gmail.com",
  "linkedin": "https://www.linkedin.com/in/msashokkumar"
}
```
---

## License

Please refer to LICENSE.