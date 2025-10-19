# Nobel Prize Data Analysis

A comprehensive data analysis project exploring Nobel Prize winners from 1901 to 2020 using Python data visualization libraries.

## Overview

This project analyzes historical Nobel Prize data to uncover patterns and insights about laureates across different categories, countries, and time periods. Using interactive visualizations with Plotly and statistical plots with Matplotlib & Seaborn, we explore trends in Nobel Prize awards over more than a century.

## Dataset

The analysis uses a comprehensive dataset containing **962 Nobel Prize entries** with the following information:

- **Time span**: 1901-2020 (119 years of Nobel Prize history)
- **Categories**: Chemistry, Literature, Physics, Medicine, Economics, Peace
- **Laureate types**: Individual winners and Organizations
- **Geographic data**: Birth countries, organization locations with ISO codes
- **Demographics**: Gender, age, institutional affiliations

### Key Data Points
- 16 columns of detailed information per laureate
- No duplicate entries
- Missing data patterns explained by laureate type (organizations vs individuals)

## Technologies Used

- **Python 3.7+**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Plotly Express** - Interactive visualizations
- **Matplotlib** - Static plotting
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment

## Analysis Features

The notebook explores several key questions:

- **Temporal trends**: How have Nobel Prize awards changed over time?
- **Geographic patterns**: Which countries produce the most laureates?
- **Gender representation**: How has gender balance evolved across categories?
- **Age demographics**: What's the typical age of Nobel Prize winners?
- **Category analysis**: Which fields dominate in different eras?
- **Institutional analysis**: Top universities and research organizations

## Getting Started

### Prerequisites
```bash
pip install -r requirements.txt
```

Or install individually:
```bash
pip install pandas numpy plotly matplotlib seaborn jupyter
```

### Running the Analysis
1. Clone this repository
2. Ensure `nobel_prize_data.csv` is in the project directory
3. Open `Nobel_Prize_Analysis.ipynb` in Jupyter Notebook
4. Run all cells to generate the complete analysis

## Data Quality Notes

- **Organizations**: 28 entries represent organizations (Peace Prize recipients) and naturally lack personal birth data
- **Individual laureates**: Some entries missing organizational affiliations (255 cases) - common for literature and peace prize winners
- **Motivations**: 88 entries have missing motivation text, primarily from early years

## Key Insights

*Run the notebook to discover fascinating patterns in Nobel Prize history, including trends in international collaboration, gender representation over time, and the evolution of scientific recognition.*

## Project Structure

```
├── Nobel_Prize_Analysis.ipynb    # Main analysis notebook
├── nobel_prize_data.csv         # Dataset (962 entries, 16 columns)
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation
```

## Contributing

Feel free to fork this project and add your own analysis or visualizations. Some ideas for enhancement:
- Network analysis of collaborations
- Predictive modeling for future trends
- Additional geographic visualizations
- Citation impact analysis

## Data Source

Nobel Prize data compiled from official Nobel Prize records, covering all categories from the prize's inception in 1901 through 2020.
