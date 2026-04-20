R Programming Practice Labs
A portfolio of hands-on R programming labs covering data analysis, visualization, and
interactive dashboard development — applied across real-world scenarios in education,
retail, and public health.
 Repository Structure
r-programming-labs/
│
├── lab1_student_performance.R       # Student grade analysis
├── lab2_retail_sales.R              # Retail store sales tracking
├── lab3_cholera_outbreak.R          # Public health case monitoring
├── dataset1_iris_analysis.R         # Iris dataset exploration
├── dataset2_airpassengers.R         # AirPassengers time series analysis
│
├── lab1_barplot.png
├── images/                          # Screenshots of outputs and plots
│   
│   
│   
│   
│   
│   
│   
│   
│   
│   
├── lab1_histogram.png
├── lab2_lineplot.png
├── lab2_piechart.png
├── lab3_linegraph.png
├── lab3_barchart.png
├── iris_scatterplot.png
├── iris_boxplot.png
├── airpassengers_trend.png
└── airpassengers_histogram.png
│
└── README.md
 Labs Overview
Lab 1 — Student Performance Analysis
Scenario: A school teacher wants to analyze examination scores and classify student
grades.
Concepts covered: Variables, vectors, factors, data frames, for-loops, if-else conditions,
summary statistics, base R visualization
Key outputs:
Grade classification: A (≥85), B (70–84), C (<70)
Mean score: 80.4 | Max: 90 | Min: 67
Bar plot of individual scores
Histogram of score distribution

Lab 2 — Retail Store Sales Analysis
Scenario: A small shop tracks daily product sales across three days to identify top
performing products.
Concepts covered: Matrices, lists, data frames, conditional filtering with for-loops, line
plots, pie charts
Key outputs:
4×3 sales matrix (products × days: Mon, Tue, Wed)
High-sales filter: Rice (120 units) and Oil (150 units) exceeded threshold
Line plot of sales trends
Pie chart of product sales distribution

Lab 3 — Cholera Outbreak Case Tracking
Scenario: A health agency monitors daily cholera cases to trigger alerts and track
growth rates.
Concepts covered: Ordered factors, for-loops, threshold-based conditional alerts, day
over-day growth rate calculation, line graphs, bar charts
Key outputs:
Risk alerts: Wednesday (80 cases) and Friday (90 cases) flagged as High Risk
Growth rate calculated using: (current - previous) / previous
Negative growth rate on Thursday indicated mid-week improvement
Line graph and bar chart of daily case trends

Dataset 1 — Iris Dataset Analysis
Scenario: Exploratory analysis of R’s built-in iris dataset to uncover species-level
patterns in flower measurements.
Dataset: 150 observations | 5 variables | 3 species (setosa, versicolor, virginica)
Concepts covered: Built-in dataset loading, str() and head() exploration, petal size
classification, scatter plots, boxplots
Key outputs:
Petal classification: Large (>5cm), Medium (>3cm), Small (≤3cm)
Average sepal length: 5.84 cm | Max petal length: 6.9 cm
Scatter plot revealing clear species clustering
Boxplot showing petal length distribution per species

Dataset 2 — AirPassengers Time Series Analysis
Scenario: An airline analyzes monthly passenger trends from 1949–1960 to plan
capacity.
Dataset: 144 monthly observations | Time series object (ts)
Concepts covered: Time series conversion, data frame construction, traffic classification,
matrix reshaping (12×10), list structures, trend visualization
Key outputs:
Traffic classification: High (>400), Medium (>250), Low (≤250)
12×10 matrix revealing August as consistently the busiest month
Compound growth pattern visible across all years
Line plot, histogram, and boxplot of passenger data
 Skills Demonstrated
Category
Tools & Concepts
Data Structures
Vectors, Matrices, Lists, Data Frames, Factors
Control Flow
For-loops, If-else conditions, Conditional filtering
Statistical Analysis
Mean, Max, Min, Growth rate calculation
Visualization
Bar plots, Histograms, Line graphs, Pie charts, Scatter plots, Boxplots
Real Datasets
iris, AirPassengers (built-in R datasets)
Time Series
ts object conversion, matrix reshaping

 How to Run
Prerequisites
Make sure R and RStudio are installed. No additional packages are required — all labs use
base R only.
Running the Labs
Open any .R file in RStudio and click Run or press Ctrl + Enter to execute line by line.

 About
Praise — Data Scientist & Analyst in Training  Nigeria  Diploma in Data Science (in
progress) | B.Sc. Economics  R · Python · SQL (T-SQL) · MongoDB · Excel
Open to freelance data analysis and visualization projects
