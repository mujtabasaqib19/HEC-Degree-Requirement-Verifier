# Degree Requirements and Transcript Generator

## Overview
The **Degree Requirements and Transcript Generator** is a comprehensive tool designed to assist students and institutions in validating academic progress against predefined degree requirements. It calculates overall GPA, checks compliance with credit requirements, visualizes credit distribution, and generates professional-grade transcripts.

## Features
- **Credit Compliance Validation**: Matches students' courses with predefined HEC requirements across various categories.
- **Overall GPA Calculation**: Computes GPA based on course grades and credit hours.
- **Visual Insights**: 
  - Bar charts for credit distribution comparison.
  - Pie charts for category-wise credit proportions.
- **Transcript Generation**: Creates PDF transcripts with detailed GPA, compliance, and course details.
- **Status Report**: Generates a text file summarizing compliance status and missing credits, if any.
- **Streamlit Integration**: Interactive web application for seamless user experience.

---

## Tech Stack
- **Python**: Core programming language.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization.
- **Streamlit**: Web application framework.
- **FPDF**: PDF generation.
- **Tempfile**: Temporary file handling for PDFs.

---

## Usage Instructions
1. **Launch Application**: Run the Streamlit application with `streamlit run app.py`.
2. **Upload CSV**: Upload a CSV file containing course details (`courseName`, `creditHour`, `grade`).
3. **View Insights**:
   - Check overall GPA.
   - Visualize compliance and credit distribution.
4. **Generate Outputs**:
   - Download status text file.
   - Generate and download the transcript PDF.

---

## Requirements
- Python 3.7+
- Libraries: 
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `streamlit`
  - `fpdf`

Install dependencies with:
```bash
pip install pandas matplotlib seaborn streamlit fpdf
```

---

## Input File Format
The input CSV must have the following columns:
- **courseName**: Name of the course.
- **creditHour**: Credit hours assigned to the course.
- **grade**: Grade received for the course.

---

## Output
- **Transcript PDF**: A professionally formatted transcript containing GPA, compliance, and course details.
- **Compliance Status File**: A text file summarizing the degree requirements compliance status.

---

## Visualizations
- **Bar Chart**: Comparison of obtained and required credits by category.
- **Pie Chart**: Proportion of credits obtained in each category.

---

## Contact
For queries or suggestions, reach out via mujtabasaqib654@gmail.com .
