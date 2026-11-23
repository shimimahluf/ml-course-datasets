# ML course datasets

Datasets for the 10th-grade Machine Learning course (AI Sciences track, Ort Yad Lebovitz, Netanya).
The course decks and Colab notebooks load the files straight from this repo, so the links stay stable.

מאגרי הנתונים של קורס למידת מכונה, כיתה י'. המצגות והמחברות טוענות את הקבצים ישירות מכאן.

## How to load a file in Colab

```python
import pandas as pd

BASE = "https://raw.githubusercontent.com/shimimahluf/ml-course-datasets/main/"
df = pd.read_csv(BASE + "penguins.csv")
```

## Files

| File | Rows | Used for | Original source |
|---|---|---|---|
| `Iris.csv` | 150 | Deck examples, KNN | UCI Machine Learning Repository, Iris (R. A. Fisher, 1936); Kaggle version with `Id` column |
| `penguins.csv` | 344 | Pandas, regression, KNN, SVM exercises | Palmer Penguins (K. Gorman, Palmer Station LTER), CC0 |
| `titanic_data.csv` | 891 | Visualization, classification | Kaggle "Titanic – Machine Learning from Disaster" (train set) |
| `diamonds.csv` | 53,940 | Visualization, regression | ggplot2 `diamonds` dataset |
| `kc_house_data.csv` | 21,613 | Linear regression | Kaggle "House Sales in King County, USA" |
| `healthcare-dataset-stroke-data.csv` | 5,110 | Optional SVM exercise | Kaggle "Stroke Prediction Dataset" |

The files are the same versions used in the 2026 unit 3 training course (Ariel Bar Yitzhak), copied here
so the course does not depend on other people's links. Licences and terms are those of the original sources.

## Images

| File | Credit |
|---|---|
| `images/lter_penguins.png` | The three penguin species — Artwork by @allison_horst (palmerpenguins) |
| `images/culmen_depth.png` | Bill length and bill depth — Artwork by @allison_horst (palmerpenguins) |
