# IPL Data Analysis Project using PySpark

This project performs comprehensive analysis of Indian Premier League (IPL) cricket data using PySpark and Python data analysis tools. The analysis focuses on understanding match statistics, player performance, and team dynamics through data-driven insights.

## Project Overview
The project analyzes IPL cricket matches data from multiple aspects including:
- Ball-by-ball analysis (runs, wickets, extras)
- Match statistics and outcomes
- Player performance metrics
- Team performance analysis
- Batting and bowling statistics

## Features
- Data processing using PySpark for efficient large-scale data handling
- Comprehensive schema definitions for structured data analysis
- Statistical analysis of match and player performance
- Data visualization using Matplotlib and Seaborn
- Interactive Jupyter notebook for analysis exploration

## Dataset
The project uses the following datasets:
- `Ball_By_Ball.csv`: Detailed ball-by-ball match data including runs, wickets, extras, and player information
- `Match.csv`: Match metadata including teams, venue, toss details, and match results
- `Player.csv`: Player information including batting hand, bowling skill, and demographics
- `Player_match.csv`: Player-specific match statistics and roles
- `Team.csv`: Team information and identifiers

## Requirements
- Python 3.x
- PySpark (for distributed data processing)
- Matplotlib (for data visualization)
- Seaborn (for statistical visualizations)
- Jupyter Notebook (for interactive analysis)

## Installation
1. Create a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Unix/macOS
```

2. Install required packages:
```bash
pip install pyspark matplotlib seaborn jupyter
```

## Project Structure
```
.
├── README.md
├── datasets/
│   ├── Ball_By_Ball.csv
│   ├── Match.csv
│   ├── Player.csv
│   ├── Player_match.csv
│   └── Team.csv
└── notebooks/
    └── analyses.ipynb
```

## Usage
1. Activate the virtual environment
2. Open the Jupyter notebook `notebooks/analyses.ipynb`
3. Run the cells to perform various analyses on the IPL data

## Contributing
Feel free to fork this repository and submit pull requests for any improvements.

## License
This project is open source and available under the MIT License. 