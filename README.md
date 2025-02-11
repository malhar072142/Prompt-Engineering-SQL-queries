# 🗃️ SQL Query Generation Using Prompt Engineering

Utilizing **Prompt Engineering** techniques to extract structured data, convert it into **JSON format**, and generate **SQL queries** for storage and retrieval.

## 📌 Overview

This project explores the application of **GPT-4 prompt engineering** for automating SQL query generation. It involves **structured data extraction** from unstructured text, **conversion to JSON**, and **SQL query generation** for database operations. The project evaluates query accuracy, readability, and SQL dialect compatibility.

## 🎯 Objectives

- Extract **company attributes** from raw text.
- Convert extracted data into **JSON format**.
- Generate SQL queries for **table creation**, **data insertion**, and **data retrieval**.
- Evaluate query performance in terms of **accuracy, readability, and SQL dialect compatibility**.

## 📂 Dataset & Processing

- **Input:** Unstructured company data stored in a text file.
- **Processing Steps:**
  - **Extract attributes** (e.g., Rank, Name, Industry, Revenue, Employees, Headquarters).
  - **Convert extracted data** to JSON format.
  - **Generate SQL queries** for structured database storage.

## 🛠️ Implementation

1. **Data Extraction & JSON Conversion**
   - Prompt designed to extract structured attributes.
   - Converted extracted data into **JSON format** for easier SQL integration.

2. **SQL Query Generation**
   - **Table Creation Query:** Schema generated with appropriate data types.
   - **Data Insertion Query:** SQL **INSERT** query generated based on JSON data.
   - **Query for Top & Bottom Ranked Companies:** Used **UNION** and **window functions**.
   - **Grouping Companies by State & Industry:** Applied **GROUP BY** functions for analysis.

## 📊 Evaluation & Insights

- **Accuracy:**
  - Extracted attributes aligned with dataset fields.
  - JSON conversion successful but required numerical data type conversion.

- **Query Formatting Issues:**
  - **Table creation query** was structurally correct but lacked **range constraints**.
  - **SQL INSERT query** was valid but had **formatting issues** due to model tokenization.
  - **State grouping query** required **SQL dialect-specific handling**.

   ```

## 📌 Future Enhancements

- **Improve prompt structure** to minimize formatting errors.
- **Enhance cross-database compatibility** for SQL dialects.
- **Refine model responses** to improve SQL query consistency.

