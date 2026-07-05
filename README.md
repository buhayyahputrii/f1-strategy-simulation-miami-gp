# Formula 1 Strategy Simulation – Miami Grand Prix 2026

This project investigates whether an earlier pit stop would have improved race performance during the 2026 Miami Grand Prix.

Using FastF1 telemetry data and a counterfactual simulation model built in Python, I evaluated alternative pit stop strategies and compared them with the actual Williams race strategy.

The objective was to determine whether stopping earlier would have produced a faster overall race time.

---

Project Objectives

• Build a counterfactual Formula 1 strategy simulation using real race data.

• Compare the actual strategy with alternative pit stop timings.

• Measure the performance impact of each strategy using total race time.

• Understand how tyre performance influenced strategic decision-making.

---

Tools

• Python

• FastF1

• Pandas

• NumPy

• Matplotlib

---

Methodology

1. Download official lap-by-lap race data using the FastF1 library.

2. Extract Carlos Sainz and Franco Colapinto lap time data.

3. Build counterfactual scenarios by changing the pit stop lap while keeping race conditions consistent.

4. Apply pit loss and tyre warm-up assumptions.

5. Compare cumulative race times between actual and simulated strategies.

---

Scenarios

Actual Strategy

• Pit Stop: Lap 32

Alternative Strategy 1

• Pit Stop: Lap 27

Alternative Strategy 2

• Pit Stop: Lap 29

---

Results

| Strategy | Total Race Time |
|----------|-----------------|
| Actual Strategy | Fastest |
| Pit Lap 27 | 7.5 seconds slower |
| Pit Lap 29 | 8.6 seconds slower |

---

Key Findings

The simulation showed that pitting earlier did not improve overall race performance.

Although an earlier stop initially appeared beneficial, the Medium tyres maintained competitive pace with minimal degradation, meaning the additional pit loss could not be recovered by the new Hard tyres.

The analysis suggests that the Williams strategy was well timed and strategically optimal under the race conditions.

---

Repository Contents

• Miami GP Python simulation

• Counterfactual strategy model

• Data visualizations

• Race strategy comparison

---

Skills Demonstrated

• Formula 1 Strategy Analysis

• Counterfactual Simulation

• Data Analysis

• Python Programming

• Motorsport Analytics

• FastF1

• Data Visualization

---

Author

Buhayyah Putri

Management Student

Interested in Business Analytics, Motorsport Strategy, Data Analysis, and Simulation.