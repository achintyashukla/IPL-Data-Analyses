# IPL Data Analysis Project using PySpark

This project performs comprehensive analysis of Indian Premier League (IPL) cricket data using PySpark and Python data analysis tools.

## Project Overview
The project analyzes IPL cricket matches data from multiple aspects including:
- Ball-by-ball analysis
- Match statistics
- Player performance
- Team analysis

## Dataset
The project uses the following datasets:
- `Ball_By_Ball.csv`: Contains ball-by-ball match details
- `Match.csv`: Contains match-level information
- `Player.csv`: Contains player information
- `Player_match.csv`: Contains player-match specific details
- `Team.csv`: Contains team information

## Requirements
- Python 3.x
- PySpark
- Matplotlib
- Seaborn

## Installation
1. Create a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Unix/macOS
```

2. Install required packages:
```bash
pip install pyspark matplotlib seaborn
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
    └── IPL_DATA_ANALYSIS.ipynb
```

## Usage
1. Activate the virtual environment
2. Open the Jupyter notebook `notebooks/IPL_DATA_ANALYSIS.ipynb`
3. Run the cells to perform various analyses on the IPL data

## Contributing
Feel free to fork this repository and submit pull requests for any improvements.

## License
This project is open source and available under the MIT License. 