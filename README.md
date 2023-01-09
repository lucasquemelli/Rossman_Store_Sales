# Rossmann Store Sales

<code><img width="100%" src="https://github.com/lucasquemelli/Rossmann_Store_Sales/blob/main/images/rossmann_img.jpeg"></code>

# 1. Business Problem

### Description

---

**Rossmann** is a real German drugstore which is available in many European countries. Their business model is the sale of products such as medicines, baby and body care, hygiene, sun protections, cosmetics, dental hygiene, household, pets, hair care, perfume, fragrances, and food products. 

**Purpose:** to forecast sales revenue of the next 6 weeks for Rossmann stores to know if we will be able to make a renovation for every store. (Fictitious purpose)

**Strategy:** we used the CRISP-DS (Cross-Industry Process - Data Science) as the main project management methodology. The predictions were delivered through a Telegram Bot in order the CFO and stakeholders check the informations using their smartphones. 

The dataset used in this project contains historical drugstore sales from 1115 Rossmann stores (Europe). Dataset description and all files may be checked and downloaded through [Kaggle - Rossmann Store Sales](https://www.kaggle.com/competitions/rossmann-store-sales/data).   

All files from the dataset were uploaded on [datasets](https://github.com/lucasquemelli/Rossmann_Store_Sales/tree/main/datasets) folder. However, the **train** file could not be uploaded on GitHub due to its size exceeds 25 MB. Therefore, we decided to load data from local repository for this project.

# 2. Business Assumptions (Formulated Hypotheses)

The assumptions (hypotheses) formulated to be tested may be seen below.

1. Stores with bigger assortments should have higher sales.
2. Stores with closer competitors should have lower sales.
3. Stores with long time competitors should have higher sales.
4. Stores with active promotions for longer periods should have higher sales.
5. Stores with more subsequent promotions should have higher sales.
6. Stores which work on Christimas holiday should have higher sales.
7. Stores should have higher sales over year.
8. Stores which work in the second semester of the year should have higher sales.
9. Stores should have higher sales on day 10 for every month.
10. Stores should have lowe sales on school holidays.
11. Stores which work on weekends should have higher sales.

# 3. Solution Strategy

**Step 01 - Data Description:** renaming features, cleaning data, changing data type, treating missing values and descriptive statistics. 

**Step 02 - Feature Engineering:** creating hypotheses mind map, hypotheses generation and feature engineering. 

**Step 03 - Feature Filtering and Selection:** rows filtering and columns selection. 

**Step 04 - Exploratory Data Analysis (EDA):** univariate analysis, bivariate analysis and multivariate analysis. 

**Step 05 - Data Preparation:** normalization, rescaling and transformation.

**Step 06 - Feature Selection:** Boruta algorihtm with Random Forest Regrresor to select the most relevant features.

**Step 07 - Machine Learning Modelling:** testing and comparing Machine Learning models.

**Step 08 - Hyperparameter Fine Tuning:** determining the optimum parameters for the chosen models. 

**Step 09 - Error Interpretation and Translation:** stores business performance, total business performance and Machine Learning performance.


# 4. Top 6 Data Insights

**Hypothesis 4:** Stores with active promotions for longer periods should have higher sales.

**False**. Few weeks after the beginning of the promotion is still profitable. The sum of sales is kept high. However, after some weeks, the sales falls down.

**Hypothesis 5:** Stores with more subsequent promotions should have higher sales.

**False**. We did not observe higher sales for consecutive promotions.

**Hypothesis 7:** Stores should have higher sales over year.

**False**. Stores presented lower sales over the years.

**Hypothesis 8:** Stores which work in the second semester of the year should have higher sales.

**False.** Stores have lower sales in the second semester of the year.

**Hypothesis 10:** Stores should have lower sales on weekends.

**True.** They have lower sales on weekends.

**Hypothesis 11:** Stores should have lower sales on school holidays.

**True.** Stores have lower sales during school holidays.
