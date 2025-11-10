

# 📊 Zomato Dataset Exploratory Data Analysis (EDA)

This repository contains an exploratory data analysis (EDA) of the Zomato dataset. The project aims to uncover insights into restaurant dynamics, such as geographical distribution, popular cuisines, pricing, and the factors influencing restaurant ratings.

-----

## 🎯 Project Goal

The primary goal of this project is to perform a comprehensive EDA on the Zomato restaurant data to:

  * **Understand the data structure**, identify missing values, and handle data cleaning.
  * **Analyze restaurant distribution** across different countries and cities.
  * **Investigate key metrics** like average cost, price range, and the number of votes.
  * **Determine the distribution of ratings** and the relationship between ratings, votes, and price.
  * **Identify the most popular and highest-rated cuisines** and restaurant types.

-----

## 💻 Dependencies and Setup

This project is built using standard Python libraries for data analysis and visualization.

### Prerequisites

  * Python (3.x)

### Installation

You can install the necessary Python packages using `pip`:

```bash
pip install pandas numpy matplotlib seaborn
```

### Data Source

The analysis uses the primary Zomato dataset (`zomato.csv`) which is assumed to be available in the working directory or linked through a platform like Kaggle.

-----

## 📋 Initial Data Exploration Summary

The initial steps covered loading the data and performing basic checks:

| Feature | Details |
| :--- | :--- |
| **Rows/Records** | 9551 |
| **Columns/Features** | 21 |
| **Data Types** | `int64` (5), `float64` (3), `object` (13) |
| **Missing Data** | Only 9 missing values in the **`Cuisines`** column. |

### Key Columns

| Column Name | Description |
| :--- | :--- |
| `Restaurant ID` | Unique ID for each restaurant. |
| `Country Code` | Code indicating the country of the restaurant. |
| `City` | Location of the restaurant. |
| `Cuisines` | Types of food offered (e.g., "French, Japanese"). |
| `Average Cost for two` | Cost for a two-person meal in local currency. |
| `Price range` | Normalized price level (1 to 4). |
| `Aggregate rating` | The average rating of the restaurant. |
| `Votes` | Number of user votes/reviews. |

-----

## 🚀 Analysis Steps (Completed & Planned)

The notebook structure follows a standard EDA workflow:

### ✅ Completed Steps

1.  **Library Imports:** Imported `pandas`, `numpy`, `matplotlib`, and `seaborn`.
2.  **Data Loading & Preview:** Loaded `zomato.csv` and checked the first 5 rows.
3.  **Data Structure Check:** Examined column names (`df.columns`) and data types/non-null counts (`df.info()`).
4.  **Descriptive Statistics:** Generated numerical summaries (`df.describe()`).
5.  **Missing Value Identification:** Identified the 9 missing values in the `Cuisines` column.

### 🔜 Planned Steps

1.  **Data Cleaning:** Handle the missing values in the `Cuisines` column (e.g., dropping or imputing).
2.  **Univariate Analysis (Numerical):** Analyze the distributions of `Aggregate rating`, `Votes`, and `Average Cost for two`.
3.  **Univariate Analysis (Categorical):** Explore the counts of `Country Code`, `City`, `Cuisines`, `Rating color`, and other categorical features.
4.  **Bivariate/Multivariate Analysis:** Investigate relationships, particularly how geographic location, price range, and availability of booking/delivery impact the `Aggregate rating` and `Votes`.

-----

## 🤝 Contribution

Feel free to fork this repository, explore the data further, and contribute your own findings or improvements to the analysis\!# EDA-Assignments
