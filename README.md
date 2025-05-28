🌍 World Happiness Decoded by AI – Data Analysis

Author: Haidar Dagham
Date: 2025
Skills, Tools & Technologies Used:
- Python Libraries: `pandas`, `numpy`, `seaborn`, `plotly`
- Notebook Environments: Jupyter Notebook, Google Colab.
- Cloud Platforms: IBM Watsonx.ai
- BI & Visualization Tools: IBM Cognos Analytics, PowerPoint.
- AI Tools: ChatGPT, DeepSeek.
- Version Control: Git & GitHub. 


---

📌 Introduction

The World Happiness Report is a globally recognized dataset that evaluates the state of happiness across countries. This project analyzes the 2016 World Happiness dataset using generative AI to automate and demonstrate a complete data analysis workflow. The objective is to uncover the economic, social, and regional factors that contribute to a better quality of life.

---

📌 Dataset Source

The dataset is derived from the **2016 World Happiness Report**, available on Kaggle under the CC0: Public Domain license.  
[Dataset on Kaggle](https://www.kaggle.com/datasets/unsdsn/world-happiness)  

📌 Column Descriptions:

| Column Name                | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| Country                   | Name of the country                                                         |
| Region                    | Region the country belongs to                                               |
| Happiness Rank            | Rank based on Happiness Score                                               |
| Happiness Score           | Metric for perceived happiness                                              |
| Economy (GDP per Capita)  | Contribution of GDP to the happiness score                                  |
| Family                    | Family support effect on happiness                                          |
| Health (Life Expectancy)  | Impact of life expectancy on happiness                                      |
| Freedom                   | Perceived freedom in decision making                                        |
| Trust (Government Corruption) | Trust in institutions' integrity                                       |
| Generosity                | Tendency toward charitable behavior                                         |
| Dystopia Residual         | Benchmark component to scale country happiness                             |

---

📌 Project Overview

This analysis aims to answer whether economic, demographic, and regional factors influence happiness levels. It uses AI-generated prompts to automate EDA and storytelling.

Key Visual Goals:
- Correlation heatmap: Economic & social indicators vs happiness
- Scatter plot: GDP per Capita vs Happiness Score by Region
- Pie chart: Regional distribution of happiness
- Choropleth map: World map of GDP with life expectancy in tooltip
- Interactive Dashboard: Visual summary in HTML
- Bar chart: GDP and Life Expectancy of top 10 happiest countries

---

📁 Folder Structure

```
📂 data/           → Contains 2016 dataset (cleaned)
📂 notebooks/      → AI-generated Jupyter analysis
📂 dashboards/     → dashboard.html output (interactive)
📂 presentations/   → Executive summary (PPTX)
📄 README.md       → Project overview & instructions
```

---

🧠 Methodology

- Data Cleaning: Filled nulls, renamed columns, handled formatting.
- EDA: Used bar charts, heatmaps, scatter, and pie charts.
- Visualization: Combined static (Seaborn/Matplotlib) with interactive (Plotly).
- Dashboard: Created with Plotly for interactivity and exploration.

---

📈 Key Insights

- Top 10 Happiest Countries: Have highest GDP and life expectancy.
- Strong Correlation: Between GDP, life expectancy, family support, and happiness.
- Low Trust Impact: Government corruption still affects lower scores in some regions.
- Regional Patterns: North America and Western Europe score consistently high.

---

💼 Applications

- Useful for public policy, education planning, and economic development.
- Demonstrates the power of generative AI in real-world data analysis workflows.

---

📝 How to Run the Code

1. Clone the repository
2. Open `World-Happiness-Decoded-by-AI_Notebook.ipynb` in Jupyter Notebook
3. Run all cells to explore and visualize data
4. Open `dashboard.html` in browser to view dashboard

---

📬 Contact
📧 Haidar@Dagham.com  
