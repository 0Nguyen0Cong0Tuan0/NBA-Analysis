# NBA Analysis Project

This project provides a comprehensive analysis of NBA data, leveraging data science and machine learning techniques to deliver insights into player and team performance. The analysis is based on data collected from official NBA statistics and Basketball Reference.

### Key Files and Directories

- **`data_collecting.ipynb`**: Contains scripts for web scraping and data collection from NBA and Basketball Reference websites.
- **`data_preprocessing.ipynb`**: Handles data cleaning, transformation, and preparation for analysis.
- **`data_overview.ipynb`**: Provides an overview of the project objectives and datasets.
- **`data_modeling.ipynb`**: Focuses on building predictive models and statistical analysis.
- **`players_analysis.ipynb`**: Analyzes player performance, including high-performing and consistent players.
- **`rookies_analysis.ipynb`**: Examines rookie player statistics and performance.
- **`teams_analysis.ipynb`**: Analyzes team performance, including per-game and total statistics.
- **`data_[basketball-reference.com]/`**: Contains raw data files collected from Basketball Reference.
- **`data_[nba.com]/`**: Contains raw data files collected from NBA.com.
- **`final_data/`**: Stores cleaned and processed datasets ready for analysis.
- **`players_cluster/`**: Includes clustering analysis for player segmentation.

## Data Sources

The project uses data from the following sources:
- [NBA Official Stats](https://www.nba.com/stats)
- [Basketball Reference](https://www.basketball-reference.com/)

### Key Datasets

- **Team Statistics**: Includes total and per-game statistics for NBA teams.
- **Player Statistics**: Comprehensive data on player performance, including rookies.
- **Season Metadata**: Information about NBA seasons, including active and defunct teams.
- **Achievements and Records**: Historical achievements and all-time records.

## Objectives

1. Provide NBA fans, analysts, and stakeholders with deeper insights into team and player performance.
2. Assist coaches, managers, and team owners in optimizing strategies and resources.
3. Showcase the application of data science and machine learning in sports analytics.

### Key Analyses

- **Players**: Identify high-performing and consistent players (2020-2025) using metrics like Efficiency (EFF).
- **Teams**: Analyze team performance metrics, including rankings, ratings, and per-game statistics.
- **Rookies**: Evaluate rookie player performance and potential.

## Usage

### Data Collection
Run the `data_collecting.ipynb` notebook to scrape and collect data from the specified sources.

### Data Preprocessing
Use the `data_preprocessing.ipynb` notebook to clean and prepare the data for analysis.

### Analysis
Explore the various analysis notebooks (`players_analysis.ipynb`, `teams_analysis.ipynb`, `rookies_analysis.ipynb`) for insights into players, teams, and rookies.

### Modeling
Leverage `data_modeling.ipynb` to build predictive models and perform advanced statistical analysis.

## Requirements

- Python 3.x
- Required libraries: `selenium`, `pandas`, `numpy`, `matplotlib`, `seaborn`, etc.

Install dependencies using:

```bash
pip install -r requirements.txt
```
## Results
The results of the analysis are stored in the `final_data/` directory and include cleaned datasets, statistical summaries, and visualizations.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
Feel free to modify this template to better suit your project's specific details.
