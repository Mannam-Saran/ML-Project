# Personalized Recipe Recommendation System

This is a comprehensive **Python-based Machine Learning project** that recommends personalized recipes to users based on their preferences, historical ratings, and nutritional profiles. The system uses collaborative filtering, content-based filtering, clustering, and visualization.

---

## Features

- **Hybrid Recommendation Engine** combining collaborative and content-based filtering.
- **Search functionality** for recipes using ingredients or keywords.
- **Ingredient substitution system** that respects dietary restrictions.
- **K-Means Clustering** for grouping recipes based on nutritional content.
- **Evaluation Metrics**: RMSE, MAE, R² score for recommendation quality.
- **Visual Analytics** including heatmaps and distribution plots.

---

## Project Structure

```
.
├── data/
│   ├── enriched_recipes.csv
│   ├── synthetic_interactions.csv
│   └── test_interactions.csv
├── results/
│   ├── evaluation_results.txt
│   ├── rating_distribution.png
│   ├── nutrition_distribution.png
│   ├── user_recipe_heatmap.png
│   └── cluster_nutrition_boxplots.png
├── recipe-recommendation-system.ipynb  # Main app logic
├── Untitled-1.ipynb                    # Clustering analysis
└── README.md
```

---

## Dependencies

This project uses the following Python libraries:

```
- ast
- collections
- datetime
- json
- matplotlib
- numpy
- os
- pandas
- pickle
- re
- scipy
- seaborn
- scikit-learn
- tqdm
- warnings
```

Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tqdm
```

---

## How to Run

### Step 1: Setup

Make sure the following datasets are present inside the `data/` folder:
- `enriched_recipes.csv`
- `synthetic_interactions.csv`
- `test_interactions.csv` (optional for evaluation)

### Step 2: Execute the System

Open and run:

```bash
jupyter notebook recipe-recommendation-system.ipynb
```

This notebook includes:
- System setup
- Model training
- Recommendation generation
- Evaluation and visualizations

### Step 3: Clustering Recipes

Run clustering experiments to explore how recipes are grouped by nutrition:

```bash
jupyter notebook Untitled-1.ipynb
```

---

## Evaluation

- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

Visual output will be saved under the `results/` folder.

---

## GitHub Repository

You can view the complete source code and commit history on GitHub:

[👉 Recipe Recommendation System Repository](https://github.com/Mannam-Saran/Recipe-Recommendation-System)

---

## Authors

Developed by students of CS:584 Machine Learning - Illinois Institute of Technology

- Jayawardhan Meesala
- Saran Mannam
- Morareddy Rahul Reddy
- Venkata Uday Boggarapu
- Sri Krishna Dhanush Bondada

