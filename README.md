# District-Wise Crop Production Analysis using Apache Spark

## Overview

This project focuses on analyzing district-wise agricultural crop production data using **Apache Spark (PySpark)**. The objective is to process and explore agricultural production patterns across different states, districts, crops, and years using distributed data processing techniques.

The project uses a dataset containing **242,000+ records** and demonstrates data cleaning, transformation, aggregation, and analytical operations using PySpark.

## Objectives

- Analyze agricultural crop production trends across different geographical regions.
- Perform data cleaning and preprocessing using Spark DataFrames.
- Apply distributed data transformations and aggregations.
- Analyze year-over-year production trends using Spark Window Functions.
- Extract meaningful insights from agricultural production data.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Apache Spark | Distributed data processing |
| PySpark | Spark API for Python |
| Spark DataFrames | Data manipulation and transformation |
| Spark SQL | Data querying and analysis |
| Window Functions | Year-over-year analysis using LAG |
| Google Colab | Development environment |

## Dataset

- **Domain:** Indian Agriculture
- **Records:** 242,000+
- **Data Type:** District-wise crop production records
- **Dimensions:** State, District, Crop, Year, and production-related attributes.

The dataset is used to explore agricultural production trends across geographical regions and different crop years.

## Project Workflow

### 1. Data Loading
- Loaded the agricultural dataset into the PySpark environment.
- Created Spark DataFrames for structured data processing.
- Examined the dataset structure and identified relevant attributes.

### 2. Data Cleaning and Preprocessing
- Inspected missing values and inconsistent records.
- Performed necessary data cleaning and preprocessing.
- Prepared the dataset for analytical operations.

### 3. Data Transformation and Analysis
- Applied Spark DataFrame transformations.
- Performed grouping and aggregation to analyze crop production across states, districts, and years.
- Used filtering and sorting operations to explore production patterns.

### 4. Window Functions
- Implemented Spark Window Functions to perform analytical calculations.
- Used the `LAG()` function to retrieve previous-year production values.
- Enabled year-over-year comparisons of agricultural production.

### 5. Insights and Exploration
- Analyzed crop production across different states and districts.
- Explored production trends across crop years.
- Identified variations in agricultural production across different regions and crops.

## Key Highlights

- Processed over **242,000 agricultural records** using PySpark.
- Applied distributed data processing techniques using Apache Spark.
- Implemented DataFrame transformations, aggregations, and Window Functions.
- Used `LAG()` for year-over-year production analysis.
- Explored agricultural trends across multiple geographical and temporal dimensions.

## Repository Structure

```text
District-Wise-Crop-Production-Analysis/
│
├── Crop_Production_Analysis.ipynb
├── dataset/
│   └── crop_production.csv
│
└── README.md
```

*Note: Update the notebook and dataset filenames to match your actual repository structure.*

## How to Run

The project was developed using Google Colab.

1. Clone the repository:

```bash
git clone <your-repository-url>
```

2. Open the Jupyter Notebook in Google Colab or a local Jupyter environment.

3. Install PySpark if it is not already available:

```bash
pip install pyspark
```

4. Upload or configure the agricultural dataset path.

5. Execute the notebook cells sequentially to perform data loading, preprocessing, transformations, and analysis.

## Learning Outcomes

Through this project, I gained practical experience in:

- Working with Apache Spark and PySpark.
- Processing structured datasets using Spark DataFrames.
- Performing data cleaning and transformation.
- Applying aggregation and analytical operations.
- Implementing Window Functions for time-based analysis.
- Understanding distributed data processing concepts.

---

**Author:** Maneesh Karlapudi

**GitHub:** https://github.com/maneesh6531
