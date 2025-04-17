
# Students Performance on Exams

This Jupyter Notebook explores a dataset related to student performance in exams, analyzing various factors that might influence scores in subjects like math, reading, and writing.

## Project Overview

The analysis is based on a dataset that includes the following features for each student:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Scores in Math, Reading, and Writing

The notebook provides:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Visualizations to highlight key patterns
- Correlation analysis between variables
- Potential insights into the impact of socioeconomic and demographic factors on academic performance

## Requirements

To run this notebook, make sure you have the following installed:

- Python 3.x
- Jupyter Notebook or JupyterLab

### Python Packages
```bash
pip install pandas numpy matplotlib seaborn
```

## Dataset
You need to download the dataset from Kaggle before running the notebook:

- Download here: [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

After downloading, place the StudentsPerformance.csv file in the same directory as the notebook.


## How to Use

1. Clone the repository or download the `.ipynb` file.
2. Open the notebook using Jupyter.
3. Run all cells in sequence to view the full analysis and visualizations.

## Insights

This analysis explored how parental education level, lunch type, and test preparation influenced student performance across math, reading, and writing exams. Key insights include:

- **Parental education level** had the strongest positive impact on student performance. Students whose parents held higher-tier degrees (e.g., bachelor's or master's) consistently scored better—possibly due to stronger study discipline instilled at home.
- **Test preparation** had the second most positive effect. Completing a preparation course led to noticeable improvements in exam scores.
- **Lunch type** also affected performance. Students who had standard lunches performed better than those receiving free/reduced lunches, suggesting a link between nutrition and cognitive function during exams.

### Negative Factors

- Not having a proper lunch had the **most detrimental effect** on student scores.
- Students whose parents had only lower-tier degrees (e.g., high school or some college) scored lower on average.
- Lack of test preparation also led to a drop in scores, though less severe than the lunch or parental education factors.

### Worst-Case Scenario

The lowest performance was observed in students who:
- Had free/reduced lunch,
- Did not complete a test preparation course,
- And had parents with lower-tier education levels.

### Recommendation

To maximize academic success, students should:
- Prioritize proper nutrition with a full, healthy lunch on test days,
- Engage in dedicated test preparation,
- And, if coming from households with less educational background, adopt structured and disciplined study habits that mirror those from higher-education households.
