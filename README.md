# Apache Spark – Distributed Data Processing Fundamentals

This repository contains an applied Apache Spark assignment developed as part of my Master’s program.  
The project focuses on **using PySpark for distributed data processing and analysis**, with an emphasis on understanding Spark’s programming model rather than performance tuning or production deployment.

The work is educational in nature and aims to build familiarity with Spark’s core abstractions through hands-on exercises.

---

## 📁 Dataset

The analysis is based on structured datasets provided during the course, loaded and processed using Spark.  
The data is used to practice distributed operations such as transformations, aggregations, and joins.

---

## 🔍 Analysis Workflow

The notebook follows a progressive structure covering the main components of Spark:

### 1. Spark Session & Environment
- Creation of a **SparkSession**
- Configuration of the execution environment
- Basic interaction with Spark DataFrames

### 2. Data Loading & Exploration
- Reading data into Spark DataFrames
- Inspecting schema and data types
- Basic exploratory operations

### 3. Data Transformations
- Column selection and transformation
- Filtering rows based on conditions
- Creation of derived columns

### 4. Aggregations & Grouped Analysis
- Grouping data using `groupBy`
- Applying aggregate functions (e.g. counts, averages)
- Interpreting aggregated results in a distributed context

### 5. Joins & Relational Operations
- Combining multiple DataFrames using joins
- Understanding how Spark handles relational-style operations at scale

The focus throughout the notebook is on **understanding Spark operations and execution logic**, not on cluster optimization.

---

## 🧠 Concepts Practiced

- Distributed data processing fundamentals
- Spark DataFrame API
- Lazy evaluation and transformations vs. actions
- Aggregations and joins in Spark
- Working with structured data in a distributed environment

---

## 🛠️ Tools & Technologies

- **Apache Spark**
  - PySpark DataFrame API

- **Python**
  - Used as the interface language for Spark operations

- **Jupyter Notebook**
  - Interactive development and experimentation

---

## 💡 Learning Outcomes

This project helped me:

- Understand the **core principles of Apache Spark**
- Become comfortable using PySpark for data manipulation
- See the differences between single-machine data processing and distributed workflows
- Apply SQL-like analytical logic in a distributed computing framework

The assignment prioritizes **conceptual understanding and correctness** over performance optimization or large-scale cluster management.

---

## 📁 Repository Contents

- `Spark_m3.ipynb` – Jupyter Notebook with Spark exercises  

---

## 👤 Author

**Jose Filgueira Orge**  
Master’s student in Data Science  
