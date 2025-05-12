# ev-delivery-route-simulation
Python-based simulation to validate electric vehicle delivery routes considering battery usage, weather, terrain, and customer time windows. Helps improve route feasibility, fleet performance, and operational efficiency for EV logistics.
# Simulation-Based Evaluation of Electric Vehicle Routes with Time Windows

This repository contains the code and supporting documentation for the thesis **"Simulation Approach to Evaluate Electric Vehicle Routes with Time Windows"** by Sumanth Meela, submitted to the University at Buffalo in May 2025.

## 📄 Thesis Abstract

This project develops a detailed simulation model to evaluate electric delivery vehicle routes by accounting for real-world energy consumption factors like wind resistance, payload, road slope, and temperature. The model also checks customer time-window compliance and provides heuristics for rerouting or customer removal to ensure on-time deliveries while optimizing battery usage.

## 🚚 Key Features

- **Dynamic Battery Consumption Modeling**
- **Route Validation Under Real-World Constraints**
- **Customer Time-Window Compliance Tracking**
- **Charging Station Queue Simulation**
- **Minimal Customer Removal Heuristic**
- **Fleet Optimization for Single and Two-Truck Scenarios**

## 📂 Contents

- `Sumanth_Meela_Thesis.pdf`: Full academic report detailing the methodology, experiments, and findings.
- `src/`: Python scripts implementing the simulation framework (to be uploaded here).
- `data/`: Example datasets (if applicable).
- `notebooks/`: Jupyter notebooks for result analysis and visualization .

## 🛠️ Methodology

The simulation incorporates:

- Vehicle dynamics using friction, drag, slope, and acceleration models.
- Weather impact using historical temperature and wind data.
- Realistic stop-and-go traffic patterns with signal wait times.
- Charging station queuing with random port availability modeling.
- Customer delivery window compliance checking.
- Heuristic-based customer removal for timely depot returns.

## 📊 Results Overview

- Verified route feasibility for Buffalo, NY deliveries.
- Demonstrated the impact of weather and auxiliary loads on battery life.
- Identified scenarios where customer removal or two-truck solutions improve delivery compliance.

## 📈 Future Work

- Dynamic traffic modeling based on time-of-day data.
- Real-world charging station usage pattern integration.
- Scalable fleet and route optimization strategies.

## 🏫 Acknowledgment

This work was conducted under the guidance of Dr. Rajan Batta at the University at Buffalo, with sponsorship from Linde.

## 📜 License

This project is provided for academic and research purposes only.

## 📞 Contact

For any questions or collaborations, please contact [Sumanth Meela](mailto:meelasumanth123@gmail.com).
