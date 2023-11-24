# Network Contagion Blocking Strategy

This project implements a network analysis to study the spread of contagion in a social network and evaluates a strategy to block this spread using dominating sets. The implementation is done in Python and utilizes libraries like NetworkX for network creation and manipulation, and Matplotlib for visualization.

## Getting Started

These instructions will guide you on how to get the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:

- Python (preferably version 3.8 or later)
- NetworkX
- Matplotlib
- Numpy
- Pandas

You can install these packages using pip. Run the following command:
pip install networkx matplotlib numpy pandas.


### Running the Script
To run the script, follow these steps:
1.Clone the Repository:
Clone this repository to your local machine using git clone.
2.Navigate to the Project Directory:
Change your directory to where the script is located with cd path/to/project.
3.Execute the Script:
Run the Python script using the Python interpreter with python contagion_network_analysis.py.
Replace contagion_network_analysis.py with the actual name of the Python script.
4.View Results:
The script will perform the network generation, contagion simulation, blocking strategy application, and comparative analysis. It will output the results to the console and save detailed data to a CSV file. Additionally, it will display visualizations of the network contagion spread.

### Script Details
1.The script executes the following actions:
2.Generates a random network based on the Erdős–Rényi model.
3.Calculates a dominating set for the network.
4.Simulates contagion spread with and without a blocking strategy.
5.Conducts comparative analysis between the dominating set strategy and a high-degree heuristic.
6.Visualizes the results using Matplotlib.
7.Calculates and prints performance metrics.
8.Tests various parameters of the contagion model and stores the results in a Pandas DataFrame, saved to a CSV file for further analysis.


### Authors
N.MONEESH
