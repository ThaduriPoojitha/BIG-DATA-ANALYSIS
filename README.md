# BIG-DATA-ANALYSIS

*COMPANY*:CODTECH IT SOLUTIONS

*NAME*:Thaduri Poojitha

*INTERN ID*:CT04DF1335

*DOMAIN*:DATA ANALYTICS

*DURATION*:4 WEEKS

*MENTOR*:NEELA SANTHOSH

##YOU HAVE TO ENTER DESCRIPTION OF YOUR TASK 
📝 Project Description:

This project showcases how to perform fundamental big data analysis using PySpark in a fully self-contained environment without uploading any CSV files. The focus is on using Apache Spark’s PySpark API within Google Colab to analyze structured data, demonstrate core data operations, and visualize results.

Instead of relying on external datasets, the project generates a sample dataset programmatically within the code. This approach is extremely useful for beginners, students, or professionals who want to understand PySpark workflows without dealing with file dependencies or complex setups.

The project mimics a real-world dataset where each row contains a product category (e.g., Books, Grocery, Fashion) and its price. This small-scale, manually defined dataset serves as a perfect model for testing Spark’s DataFrame functionalities in a lightweight, yet practical, context.
🛠️ Tools and Technologies Used:

🔹 Google Colab:

Google Colab is a free cloud-based platform for running Python code in Jupyter notebooks. It eliminates the need for any local setup and supports third-party packages like PySpark. In this project, Colab is used to:

Run Python and PySpark code

Visualize data with charts

Easily test and share notebooks


🔹 PySpark (Apache Spark):

PySpark is the Python interface to Apache Spark, a distributed computing engine used for processing massive datasets efficiently. Although this project uses a small dataset, it demonstrates:

Creation and use of Spark DataFrames

Schema definition and data validation

Core transformations and aggregations (e.g., group by, count, average)
🔹 Python Libraries:

Matplotlib: Used for visualizing grouped data (e.g., count per category) through bar charts.

Pandas (optional): Used briefly for converting data into a form suitable for plotting.
📦 Dataset Structure:

The dataset is hardcoded as a list of tuples. Each tuple consists of:

category: A string (e.g., "Books")

price: An integer (e.g., 150)

Example data:
[("Books", 150),
 ("Grocery", 300),
 ("Books", 200),
 ("Grocery", 250),
 ("Fashion", 400)]

This dataset is converted into a Spark DataFrame using a defined schema.
🔍 Operations Performed:

1. Spark Session Initialization: The code begins by setting up a Spark session using SparkSession.builder.

2. Schema & DataFrame Creation: A schema is defined using StructType and StructField. The data is loaded into a Spark DataFrame.
3. Exploratory Analysis:

Displaying the schema and sample records

Grouping data by category and counting records

Calculating average, minimum, and maximum prices

4. Visualization: A bar chart is created using Matplotlib to show the number of records per product category. This gives a quick visual overview of the distribution.

5. Session Termination: The Spark session is properly closed using spark.stop().

#OUTPUT

![Image](https://github.com/user-attachments/assets/daeb4475-1ea2-49bf-b474-9ab9de3243dd)
