# Machine Maintenance Simulation and Cost Analysis

## Project Overview

This project explores machine failures, maintenance requirements, downtime, and operational costs through an Excel-based simulation. It evaluates three different scenarios (A, B, and C) across six types of manufacturing machines.

The simulation uses generated data to represent machine operating conditions and maintenance activities. Python was also used to analyze and visualize the results, making it easier to compare the scenarios and understand their cost implications.

## Objectives

- Simulate machine failures and maintenance activities.
- Examine the relationship between failure rates and maintenance requirements.
- Calculate maintenance and downtime costs.
- Compare operational outcomes across three scenarios.
- Visualize the results to support maintenance planning and decision-making.

## Machine Types

The simulation covers six machine types:

1. CNC Machine
2. Conveyor Belt
3. Robotic Arm
4. Turning Machine
5. Lathe Machine
6. Hydraulic Press

## Methodology

### 1. Excel-Based Simulation

Microsoft Excel was used to build the simulation and calculate the results.

The simulation incorporates:
- Failure rates.
- Maintenance durations.
- Number of machines.
- Maintenance costs.
- Downtime costs.
- Random numbers to simulate failure occurrences.

Failure times are calculated using the simulation's failure-rate and random-number inputs. When maintenance is required, machines are taken offline for the specified maintenance duration.

Excel formulas, including `IF` and `SUM`, were used to perform calculations and evaluate maintenance-related costs.

### 2. Scenario Analysis

Three scenarios (A, B, and C) were evaluated using different simulation inputs and operating conditions.

The results were compared based on:
- Average failure rate.
- Average maintenance time.
- Average number of machines.
- Maintenance costs.
- Downtime costs.
- Total costs.

### 3. Python Data Visualization

Python was used to organize and visualize the simulation results.

**Libraries:**
- Pandas – Data organization and analysis.
- Matplotlib – Data visualization.

The visualizations include:
- Failure-rate comparisons across machine types and scenarios.
- Maintenance-cost comparisons.
- Downtime-cost comparisons.
- Total-cost comparisons.
- Overall scenario performance comparisons.

## Results

The simulation produced the following scenario-level results:

| Metric | Scenario A | Scenario B | Scenario C |
|---|---:|---:|---:|
| Average Failure Rate | 7.67 | 5.50 | 6.83 |
| Average Maintenance Time (hours) | 3.67 | 2.83 | 3.17 |
| Average Number of Machines | 12.83 | 11.33 | 13.33 |
| Maintenance Costs ($) | 505.17 | 188.45 | 498.58 |
| Downtime Costs ($) | 711.49 | 346.18 | 936.55 |
| Total Costs ($) | 1,216.67 | 534.63 | 1,435.13 |

### Key Observations

- Scenario B recorded the lowest total cost among the three scenarios, at $534.63.
- Scenario C recorded the highest total cost, at $1,435.13, with downtime costs contributing significantly.
- Scenario A had the highest average failure rate.
- Scenario B also had the lowest average maintenance time.

These results should be interpreted in the context of each scenario's different simulation inputs and operating conditions.

## Project Files

| File | Description |
|---|---|
| `machine-maintenance-simulation.xlsx` | Excel workbook containing the simulation. |
| `machine-maintenance-simulation-report.docx` | Project report documenting the work. |
| `simulation_senarios_plots.ipynb` | Jupyter Notebook containing Python visualizations. |

## Tools and Technologies

- Microsoft Excel
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Limitations

- The simulation uses generated data rather than actual industrial machine-maintenance records.
- The results depend on the assumptions and input parameters assigned to each scenario.
- The simulation provides a simplified representation of machine failures and maintenance operations.

## Conclusion

This project demonstrates how simulation and data visualization can be used to explore machine maintenance operations and compare their associated
