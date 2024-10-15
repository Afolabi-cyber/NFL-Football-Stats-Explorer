# 🏈 NFL Football Stats Explorer - Rushing Statistics

Welcome to the **NFL Football Stats Explorer**! This application allows users to explore NFL rushing statistics in an interactive and user-friendly way using **Streamlit**. The app performs web scraping to gather data from **Pro Football Reference** and presents it in a filterable and downloadable format. Additionally, users can visualize statistical relationships with a heatmap for deeper insights.

## 🔧 Key Features

- **Web Scraping:** Automatically fetches NFL rushing stats for the selected year from [Pro Football Reference](https://www.pro-football-reference.com/).
- **Interactive Filters:** 
  - Filter by **team** and **position** to display relevant player stats.
  - Display filtered data directly in the app.
- **Download Data:** Export the filtered player statistics as a CSV file.
- **Visualization:**
  - Generate an **intercorrelation heatmap** to identify relationships between different rushing stats.
  
## 🛠️ Built With

- **Streamlit** - A fast, interactive, and intuitive framework for building data-driven web apps.
- **Python Libraries:** 
  - `pandas` for data manipulation and analysis.
  - `numpy` for numerical computations.
  - `seaborn` and `matplotlib` for data visualization.
  - `base64` for handling CSV download functionality.

## 🚀 Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

Ensure you have **Python 3.7+** installed on your machine. You can download it [here](https://www.python.org/downloads/).

### Installation

1. **Clone the repo:**

   ```bash
   git clone https://github.com/your-username/NFL-Football-Stats-Explorer.git
   cd NFL-Football-Stats-Explorer
