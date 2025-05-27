# InsightWizard: AI Data Analyst & Storyteller

InsightWizard is a Python-based project that analyzes a stock market dataset, performs data cleaning, exploratory data analysis (EDA), and visualization, and uses AI to generate plain-language summaries of key insights. This project is designed to help users understand their data and make informed decisions.

---

## Features

- **Data Cleaning**: Handles missing values by filling numeric columns with their mean and categorical columns with "Unknown".
- **Exploratory Data Analysis (EDA)**:
  - Displays dataset information and descriptive statistics.
  - Visualizes trends in stock prices and trading volume.
- **AI-Powered Insights**: Uses OpenAI's GPT models to generate plain-language summaries of the dataset insights.
- **Caching**: Saves AI-generated summaries to avoid redundant API calls.

---

## Requirements

- Python 3.8 or higher
- Required Python libraries:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `openpyxl`
  - `requests`
  - `python-dotenv`

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/insight_wizard_project.git
   cd insight_wizard_project