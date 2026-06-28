# Netflix Global Content Strategy Analysis

## Project Overview

This project analyzes Netflix's global content catalog to understand how the platform's content portfolio is distributed across countries, content types, audience ratings, and genres. The objective is to transform raw catalog data into meaningful business insights that can support strategic content planning and portfolio evaluation.

The analysis follows a structured business-oriented workflow, beginning with data quality assessment and cleaning, followed by exploratory analysis, business interpretation, and evidence-based recommendations. Throughout the project, emphasis is placed on communicating insights while acknowledging the limitations of the available dataset.

## Business Problem

Netflix offers content from multiple countries across different genres and audience categories. Understanding how this content is distributed, how the catalog has evolved over time, and whether the portfolio is well diversified can help support strategic content planning.

This project analyzes Netflix's content catalog to identify meaningful patterns and generate business insights that can support future content acquisition and portfolio decisions.

## Project Objectives

This analysis was conducted to answer the following business questions:

- Assess the geographic distribution of Netflix's content catalog across different countries.
- Evaluate the balance between Movies and TV Shows within the platform.
- Analyze how Netflix's content library has evolved over time.
- Examine audience ratings and genre distribution to understand portfolio diversification.
- Generate evidence-based business insights and strategic recommendations based on the available data.

## Dataset Information

| Attribute         | Details                     |
| ----------------- | --------------------------- |
| **Dataset**       | Netflix Movies and TV Shows |
| **Source**        | Kaggle                      |
| **Records**       | 8,807 titles                |
| **Features**      | 12 columns                  |
| **Content Types** | Movies and TV Shows         |

### Key Features

- **type** – Content type (Movie or TV Show)
- **country** – Country of production
- **release_year** – Year of release
- **rating** – Audience rating classification
- **listed_in** – Genre(s)
- **duration** – Runtime or number of seasons

### Dataset Limitations

The dataset represents Netflix's content catalog and does not include business performance metrics such as revenue, watch time, subscriber engagement, production budgets, or licensing costs. As a result, all recommendations in this project are based on catalog characteristics rather than financial performance.

## Project Workflow

```text
Business Understanding
        │
        ▼
Data Quality Assessment
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Business Insights
        │
        ▼
Strategic Recommendations
```

## Key Findings

- The Netflix content catalog is geographically concentrated, with the top five content-producing countries contributing approximately **63.68%** of all titles.
- Movies account for nearly **70%** of the catalog, indicating that feature-length content remains the dominant offering.
- Content production experienced significant growth over time, with a noticeable decline after 2019 that requires additional business context for interpretation.
- Genre analysis suggests that Netflix maintains a diversified content portfolio, reducing dependence on a limited set of genres.
- Due to the absence of financial and engagement metrics, the findings should be interpreted as catalog-level insights rather than direct business performance indicators.

## Business Recommendations

Based on the analysis, the following strategic actions are recommended:

- Further investigate emerging content-producing countries to identify opportunities for expanding Netflix's global content portfolio.
- Continue maintaining a balanced mix of Movies and TV Shows while considering regional audience preferences.
- Monitor long-term content production trends to understand the factors influencing changes in catalog growth.
- Preserve a diversified genre portfolio to reduce concentration risk and serve a broader audience base.
- Combine catalog-level analysis with financial and engagement metrics before making major investment or content acquisition decisions.

## Repository Structure

The project is organized into separate folders to improve readability and m

```text
Netflix-Global-Content-Strategy-Analysis/
│
├── data/
│   └── netflix_titles.csv
│
├── notebook/
│   └── Netflix_Global_Content_Strategy_Analysis.ipynb
│
├── images/
│
├── presentation/
│
├── README.md
├── requirements.txt
└── LICENSE
```

## Technologies Used

Python
Pandas
NumPy
Matplotlib
Jupyter Notebook
Git
GitHub

## How to Run the Project

1. Clone this repository.
2. Install the required Python libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook located in the `notebook/` folder.
4. Run the notebook from top to bottom to reproduce the complete analysis.

## Future Improvements

Future versions of this project could be extended by incorporating additional business data such as:

- Revenue generated by individual titles
- Watch time and audience engagement metrics
- Production and licensing costs
- Original vs. licensed content analysis
- Interactive dashboards using Power BI or Tableau
- Predictive models for content performance

## Author

**B.Sujay**

Aspiring Data Analyst with an interest in business analytics, data visualization, and data-driven decision-making.

Thank you for exploring this project. Feedback and suggestions are always welcome.
