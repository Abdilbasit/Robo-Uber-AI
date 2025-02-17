# Robo-Uber-AI

Robo-Uber-AI is a simulation project that emulates an autonomous ride-hailing system inspired by modern on-demand transportation services. This project creates a grid-based virtual world in which taxi agents, a centralized dispatcher, and dynamic fare requests interact in real time. It serves as a testbed for exploring concepts in autonomous navigation, dynamic routing, fare allocation, and traffic management.

## Features

- **Grid-Based Virtual World:** A simulation environment constructed from interconnected nodes (junctions) and edges (streets) representing a city grid.
- **Dynamic Fare Generation:** Fares (ride requests) are generated probabilistically at various nodes, simulating real-world demand patterns.
- **Autonomous Taxis:** Taxi agents come on duty, bid for fares, navigate through the network, pick up passengers, and drop them off at their destinations.
- **Centralized Dispatcher:** A dispatcher manages fare allocation by receiving bids from taxis and assigning fares based on availability and cost.
- **Traffic Simulation:** The simulation incorporates traffic conditions at nodes, affecting taxi movement and fare pick-up timings.
- **Visualization:** Uses Pygame for real-time visualization of the simulation along with Matplotlib for output analysis.

