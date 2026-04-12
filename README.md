# DATA200 Final Project

This repository contains our DATA200 final project on NBA player analytics. The project combines:
- **Regression** for predicting player `PTS` and estimating `PER`
- **Classification** for broad role grouping (e.g., guard vs big profiles)
- **Clustering** for exploring player archetypes

The final submission is consolidated in one notebook, with supporting model notebooks kept in the `Models` folder.

## Project File Structure

| Path | Type | Description |
|---|---|---|
| `Data/` | Folder | Raw datasets used in analysis and modeling |
| `Data/player_basic.csv` | Dataset | Basic player-level statistics |
| `Data/player_advanced.csv` | Dataset | Advanced player-level statistics |
| `Data/NBA Stats.csv` | Dataset | Additional NBA stats reference file |
| `Data/nba-2024-UTC.csv` | Dataset | Additional NBA season data |
| `Data/nbateamdata.csv` | Dataset | Team-level NBA statistics |
| `Models/` | Folder | Individual model notebooks |
| `Models/Regression.ipynb` | Notebook | Regression workflows (`PTS`, `PER`) |
| `Models/Classification.ipynb` | Notebook | Classification and clustering workflows |
| `Final_Notebook.ipynb` | Notebook | Combined final notebook with full end-to-end analysis |

## Notes

- Place datasets in the `Data/` folder.
- Open and run `Final_Notebook.ipynb` top-to-bottom for the complete project output.