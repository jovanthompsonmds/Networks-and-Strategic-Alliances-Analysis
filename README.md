# Networks and Strategic Alliances Analysis

## Overview
This project analyzes financial ties and strategic alliances between entities using network analysis techniques. It employs centrality measures, egocentric graphs, and visualizations to identify key players and potential alliances within the network. The dataset represents financial connections between S&P 500 companies, highlighting strategic opportunities and challenges.

## Features
- **Network Analysis**: Explore financial relationships as a network.
- **Data Processing**: Analyze a financial ties matrix to extract actionable insights.
- **Key Metrics**: 
  - Degree, betweenness, and closeness centrality.
  - Eigenvector centrality for assessing influence and prestige.
- **Interactive Visualizations**: Generate graphs to represent egocentric networks and overall structure.
- **Strategic Insights**: 
  - Identify strong and weak ties.
  - Detect structural holes and assess their impact on social cohesion.
  - Analyze challenges such as network congestion or isolated entities.

## Files
### 1. `Networks and Strategic Alliances Analysis.ipynb`
Contains Python code for:
- Loading and preprocessing the dataset.
- Performing network analysis.
- Generating visualizations and calculating centrality metrics.

### 2. `FinancialTies.xlsx`
This Excel file:
- Contains data representing financial ties between entities.
- Serves as the input dataset for the analysis.

## Requirements
- Python 3.8 or higher
- Required Python libraries:
  - `pandas`
  - `networkx`
  - `matplotlib`
  - `openpyxl` (for reading Excel files)

- Install the dependencies using:
  - pip install pandas networkx matplotlib openpyxl

## Usage
1. Clone the repository:
   git clone https://github.com/yourusername/Networks-and-Strategic-Alliances-Analysis.git
2. Navigate to the project directory: 
   cd Networks-and-Strategic-Alliances-Analysis
3. Open the Jupyter Notebook:
   jupyter notebook "Networks and Strategic Alliances Analysis.ipynb"
4. Run the cells to:
   - Load and preprocess the financial ties data.
   - Analyze the network using centrality metrics.
   - Visualize the network and egocentric graphs.
   - Extract insights into strategic alliances and challenges.

## Insights
This project helps in:
- Identify central entities and their roles in the network.
- Understand clustering and potential for alliances.
- Highlight weak and strong ties and their implications.
- Detect structural holes and opportunities for strategic brokering.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request with improvements or new features.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
Developed by Jovan Thompson as part of a data science portfolio project.
