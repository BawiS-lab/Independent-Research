# Vulnerability Detection Using ChatGPT

This repository contains the materials and resources for the research paper: **"The Effect of Code Complexity on ChatGPT’s Vulnerability Detection Accuracy"**. The study investigates ChatGPT's ability to detect vulnerabilities in C and C++ code and examines the relationship between code complexity, lines of code (LOC), and detection accuracy.

## Overview
The research explores the following key questions:
1. **Is ChatGPT able to detect vulnerabilities in the code?**
2. **Does the vulnerability reported by ChatGPT match the recorded vulnerability in the dataset?**
3. **What is the relationship between source code LOC and ChatGPT's ability to detect vulnerabilities correctly?**
4. **What is the relationship between source code complexity and ChatGPT's ability to detect vulnerabilities correctly?**

## Repository Contents
- **Research Paper**: [Research_Paper.pdf](Research_Paper.pdf)  
  The full paper detailing the methodology, results, and findings.
- **Dataset Used**: [all_c_cpp_release2.0.csv.zip](all_c_cpp_release2.0.csv.zip)  
  A subset of the dataset titled "A C/C++ Code Vulnerability Dataset with Code Changes and CVE Summaries," used for analysis.  
  Original dataset source: [GitHub Repository](https://github.com/ZeoVan/MSR_20_Code_vulnerability_CSV_Dataset/blob/master/README.md).
- **Jupyter Notebook Scripts**: [file.ipynb](file.ipynb)  
  Python scripts used to automate dataset preprocessing, vulnerability detection with ChatGPT, and code complexity analysis.

