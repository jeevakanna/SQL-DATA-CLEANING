#  EXPLORITARY DATA ANALYSIS (single table)

# 🎯 Project Objective
Transform a raw laptop dataset into a clean, structured, and analysis-ready format. Apply data cleaning, formatting, and normalization techniques using SQL. perform exploritary data analysis using concepts like (select,where,gruoup by,order by,aggregation function,windows finction)

# 🛠 Tools & Technologies

MySQL (Data cleaning, transformation, normalization)

Data Modeling Concepts: Normalization, Formatting, Deduplication
# 🔍 Process Overview

Data Import – Loaded CSV into MySQL database

Data Cleaning – Removed duplicates, checked for missing/wrong values

Formatting – Converted text-based numbers (RAM, Weight, Inches) into numeric formats

Normalization – Split complex fields like CPU, GPU, Memory into structured columns

Optimization – Dropped unnecessary columns and finalized clean dataset

# 🧹 Data Cleaning & Formatting
Removed Duplicates using ROW_NUMBER() → ✅ No duplicates found

Formatted Columns:

• Inches → Decimal (3,1)

• Weight → Numeric WEIGHT_KG

• RAM → Integer RAM_GB

# 🔄 Data Normalization
CPU Normalization:

• Intel Core i5 7200U → CPU_BRAND: Intel, CPU_MODEL: Core i5 7200U

Memory Normalization:

• 256GB SSD → MEMORY_SIZE_GB: 256, MEMORY_TYPE: SSD

• Converted 1TB → 1000 GB, 2TB → 2000 GB

GPU Normalization:

• Nvidia GeForce GTX 1050 → GPU: Nvidia, GPU_MODEL: GeForce GTX 1050

# ✅ Key Outcomes
Built a clean, structured laptop dataset ready for analytics

Applied best practices in SQL-based data cleaning:

• Deduplication

• Formatting & conversions

• Feature extraction

• Normalization

# (EDA) conducted 

> select

> where

>group by

> having

>order by

> aggregation function

> windows function 


Dataset is now usable for BI dashboards and trend insights
