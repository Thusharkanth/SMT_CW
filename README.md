# Simulation and Analysis of Customer Queuing System in a Bank Using R

## Project Overview
This project simulates a bank's queuing system to analyze customer wait times and evaluate the impact of adding an additional service counter. The simulation is implemented in R using probabilistic models.

## Scenario
- **System**: Two service counters with single servers each.
- **Arrivals**: Poisson distribution (avg. 10 customers/hour).
- **Service Time**: Exponential distribution (avg. 5 minutes/customer).
- **Queue Policy**: First-come, first-served (FCFS).
- **Goal**: Determine if an additional counter is needed (threshold: avg. wait time > 15 minutes).

## Tasks
1. **Model Development**  
   - Formulate the queuing system using probabilistic models.
   - Implement simulation in R (e.g., `queueing` package or custom functions).
   - Simulate for an 8-hour workday (480 minutes).

2. **Analysis & Interpretation**  
   - Calculate key metrics:  
     - Average queue length  
     - Average waiting time  
     - Server utilization  
   - Evaluate impact of adding a third counter.
   - Discuss operational implications.

3. **Visualization & Reporting**  
   - Create histograms, line charts, etc.
   - Summarize methodology, results, and recommendations.


