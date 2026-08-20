# Data Visualizations with Python

A completed data visualization lab using Python and Matplotlib. The project demonstrates how different chart types can be selected and constructed to communicate categorical comparisons, relationships between numerical variables, and distributions.

## Business Context

In this lab, I take on the role of a data analyst and work through three small real-world visualization scenarios. Each exercise focuses on choosing and building an appropriate visualization while using clear titles, axis labels, and legends where appropriate.

## Objectives

- Create and label a bar chart with Matplotlib
- Create and interpret a scatter plot
- Create and interpret a histogram
- Apply visualization best practices such as descriptive titles and axis labels
- Use visualizations to communicate useful observations from data

## Technologies

- Python
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

## Analysis

### 1. Jim's Video Library — Bar Chart

The first visualization compares the number of movies in six genres: Crime, Sci/fi, Drama, Comedy, Action, and Documentary.

A bar chart is appropriate because the goal is to compare counts across discrete categories. Comedy is the largest category with 50 movies, while Documentary is the smallest with 5.

### 2. Consumer Cars — Scatter Plot

The second visualization examines the relationship between vehicle weight and miles per gallon (MPG).

A scatter plot is appropriate because both variables are numerical and the goal is to examine their relationship. The plotted observations show an overall negative relationship: heavier vehicles generally tend to have lower fuel economy.

### 3. Customer Waiting Times — Histogram

The final visualization examines waiting times recorded for 20 bank customers.

A histogram groups the observations into five bins, making it easier to understand the distribution of waiting times and identify where customer waits are concentrated.

## Running the Notebook

The completed analysis is contained in `index.ipynb`.

You can run it locally with Jupyter Notebook/JupyterLab or open it directly in Google Colab:

[Open the completed notebook in Google Colab](https://colab.research.google.com/github/ROUSE-prog/DS_Course1_Week1_Module4_VizLab/blob/complete-data-visualization-lab/index.ipynb)

Once the notebook is open, select **Runtime → Run all** to execute the cells from top to bottom and render all three visualizations.

## Key Takeaways

This lab demonstrates that the type of visualization should follow the analytical question:

- **Bar charts** are useful for comparing values across categories.
- **Scatter plots** are useful for examining relationships between numerical variables.
- **Histograms** are useful for understanding the distribution of a numerical variable.

Clear titles, axis labels, and legends make visualizations easier to understand and help turn raw data into an effective analytical story.

## Repository Structure

```text
DS_Course1_Week1_Module4_VizLab/
├── index.ipynb    # Completed visualization lab
├── README.md      # Project overview and analysis
└── LICENSE.md
```

## Author

Steven Rouse
