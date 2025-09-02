# Recipe Site EDA

This project explores recipe site traffic data through Exploratory Data Analysis (EDA).  
The dataset contains nutritional values, categories, and servings for different recipes.

---

## Files Included
- **notebook_with_EDA.ipynb** → Complete Jupyter Notebook with data cleaning and visualizations.
- **cleaned_recipe_data.csv** → Cleaned dataset after handling missing values and fixing columns.
- **category_distribution.png** → Bar chart showing how many recipes fall into each food category.
- **calories_distribution.png** → Histogram showing the distribution of calories across all recipes.
- **correlation_heatmap.png** → Heatmap showing correlations between nutritional values (calories, carbs, sugar, protein, servings).
- **calories_by_category.png** → Boxplot comparing calorie ranges across different recipe categories.
- **README.md** → Project overview and usage instructions.
- **requirements.txt** → Python dependencies.

---

## Visuals Explained

### 1. Category Distribution  
Shows which recipe categories are most common in the dataset. Helps identify dominant food types.  
![Category Distribution](category_distribution.png)

---

### 2. Calories Distribution  
Displays how calories are spread across recipes. Useful to see if most recipes are low, medium, or high calorie.  
![Calories Distribution](calories_distribution.png)

---

### 3. Correlation Heatmap  
Illustrates relationships between nutritional values. For example, calories vs. carbohydrates or sugar.  
![Correlation Heatmap](correlation_heatmap.png)

---

### 4. Calories by Category  
Compares calorie levels across categories (e.g., Beverages vs. Breakfast). Highlights which categories are calorie-dense.  
![Calories by Category](calories_by_category.png)

---

## How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/recipe-site-EDA.git
