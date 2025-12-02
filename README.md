# Actuarial Reserving Model and Data Processing

## 🎯 Project Objective

This project demonstrates the development of a core actuarial model used for calculating financial reserves (technical provisions). The objective is to apply Python and the `pandas` library to manage structured data, perform iterative calculations, and accurately determine the required reserves over multiple periods. This is a fundamental task in insurance and pension fund management to ensure long-term solvency.

## 🛠️ Tools and Libraries Utilized

The analysis was executed in a Python environment utilizing the following libraries:

* **`pandas`**: Crucial for reading, structuring, and manipulating the input data (likely a table of cash flows, premiums, and claims) represented by the `df5` DataFrame.
* **`numpy`**: Utilized for efficient numerical array operations and complex mathematical calculations inherent in reserve modeling.

## 📊 Methodology and Modeling

The core of the project involves a complex reserve calculation process:

1.  **Data Structuring:** Input data (premiums, benefits, cash flows) is structured into a `pandas` DataFrame (`df5`) for efficient indexing and calculation.
2.  **Iterative Reserve Calculation:** The model performs iterative calculations across periods to determine the necessary reserve amount (`reservas[i]`) at various points in time. The process involves precise index-based subtraction and summation of cash flows.
3.  **Output:** The final output is the calculated reserve figure, essential for financial reporting and solvency checks.

## ✨ Competencies Showcased.

* **Core Actuarial Function:** Direct experience in programming a model for financial/technical reserve calculation—a high-value skill for any insurance or risk-related position.
* **Structured Data Management:** Proven proficiency in using `pandas` for complex financial data manipulation, moving beyond basic data entry.
* **Code-Based Solutions:** Ability to translate complex, manual calculations (often done in Excel) into automated, auditable, and scalable Python code.
