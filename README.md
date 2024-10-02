# Vehicle Routing Problem Optimization using Genetic Algorithms

This project provides an implementation of a **Vehicle Routing Problem (VRP)** solution using **Genetic Algorithms (GA)**. The VRP involves determining optimal routes for a fleet of vehicles to service multiple locations from a single depot, minimizing total travel distance and balancing routes.

## Project Overview

The **Vehicle Routing Problem (VRP)** is a common optimization problem in logistics and supply chain management. This project uses a Genetic Algorithm to find the optimal set of routes for vehicles starting from a central depot, visiting multiple locations, and returning to the depot. The aim is to minimize the total distance traveled and balance the workload among vehicles.

## Features

- **Random Location Generation**: Randomly generates delivery locations and depot.
- **Multi-Objective Optimization**: Minimizes both total distance and route imbalance.
- **Visualization**: Visualize the optimal routes generated by the algorithm.
- **Scalable**: Easily customizable for different numbers of vehicles and locations.

## Installation

### Prerequisites

Ensure you have Python 3.x installed on your system.

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Hakuna77Matata/OPTIMIZATION-FOR-VEHICLE-ROUTING-PROBLEM-USING-GENETIC-ALGORITHMS.git
    cd OPTIMIZATION-FOR-VEHICLE-ROUTING-PROBLEM-USING-GENETIC-ALGORITHMS
    ```

2. **Set up a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Project Structure

VehicleRouting/ │ ├── code/ │ ├── vrp_genetic_algorithm.py # Main script containing the VRP solution │ ├── results/ │ └── plots/ # Folder to store output plots │ ├── venv/ # Virtual environment directory (optional) ├── requirements.txt # Python dependencies ├── README.md # Project documentation (this file) └── .gitignore # Ignored files (e.g., venv, data files)


## Usage

After setting up the project, you can run the VRP optimization algorithm with the following command:

```bash
python code/vrp_genetic_algorithm.py
