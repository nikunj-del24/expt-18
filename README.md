# ex-18
# Nikunj Deep Upadhyay
# ENTC B1
# PRN 25070123081



THEORY
1. Data Visualization
Data visualization is the graphical representation of data using plots, charts, and graphs. It helps in:

Understanding patterns and trends

Detecting outliers

Comparing datasets

Making data-driven decisions

Common libraries used:

Matplotlib → basic plotting

Seaborn → advanced statistical visualization

Pandas → data handling

NumPy → numerical operations

2. Dataset Creation
A dataset is created using Pandas DataFrame with:

Categorical data → Category

Numerical data → Values, Sales, Profit

Random values are generated using:

np.random.seed() → ensures reproducibility

np.random.randint() → generates random integers

3. Area Plot
Displays quantitative data as filled regions

Useful for showing trends over categories or time

Created using plt.fill_between()

Shows how values vary across categories.

4. Multiple Area Plot (Sales vs Profit)
Two area plots combined

Helps compare multiple variables

Uses transparency (alpha) and labels

5. Pie Chart
Represents data as proportions of a whole

Each slice shows percentage contribution

Created using plt.pie()

6. Donut Chart
Modified pie chart with a hole in the center

Improves readability

Created by adding a circle over a pie chart

7. Boxplot
Shows distribution of data

Displays:

Minimum

Maximum

Median

Quartiles

Outliers

Used for outlier detection

8. Heatmap (Correlation Matrix)
Visual representation of correlation between variables

Correlation value range:

+1 → strong positive

0 → no correlation

-1 → strong negative

Created using:

df.corr()

sns.heatmap()

9. Bubble Plot
Extension of scatter plot

Uses 3 variables:

X-axis → Sales

Y-axis → Profit

Bubble size → Values

Helps visualize multi-dimensional data

10. Seaborn Bubble Plot
Enhanced version of scatter plot

Adds:

Color (hue)

Size scaling (sizes)

Better aesthetics

ALGORITHM
Step 1: Import Libraries
Import required libraries:

NumPy

Pandas

Matplotlib

Seaborn

Step 2: Create Dataset
Set random seed using np.random.seed()

Create a dictionary with:

Category

Values

Sales (random values)

Profit (random values)

Convert into DataFrame

Step 3: Area Plot
Initialize figure

Use fill_between()

Set title, labels

Display plot

Step 4: Multiple Area Plot
Apply Seaborn style

Plot Sales using fill_between()

Plot Profit using fill_between()

Add legend

Show plot

Step 5: Pie Chart
Use plt.pie()

Add labels and percentage format

Display chart

Step 6: Donut Chart
Create pie chart

Draw white circle at center

Overlay circle on pie chart

Show plot

Step 7: Boxplot
Use sns.boxplot()

Pass numerical column

Show plot

Step 8: Heatmap (Correlation)
Select numerical columns

Compute correlation using corr()

Plot using sns.heatmap()

Enable annotations

Display

Step 9: Bubble Plot (Matplotlib)
Use plt.scatter()

Set:

X → Sales

Y → Profit

Size → Values

Display plot

Step 10: Bubble Plot (Seaborn)
Use sns.scatterplot()

Assign:

X, Y axes

Size parameter

Hue parameter

Adjust size range

Display



Importance of visualization in data analysis
