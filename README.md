# LinkedIn Job Postings Analysis

## Project Overview

This project focuses on analyzing job postings scraped from LinkedIn, a popular platform for job seekers and employers. The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings), where a contributor provided a collection of job postings that needed thorough cleaning and analysis. 

One of the standout features of this project is its **entire reproducibility**. By following the steps outlined in the Jupyter Notebook (`Project1notebook.ipynb`), users can easily replicate the entire data cleaning and analysis process. The project includes all necessary scripts and dependencies, ensuring that anyone can achieve the same results using the same dataset.

### Dataset Description

The raw data contained various job postings, including job titles, descriptions, salary ranges, work types, and application methods. However, the dataset was messy, requiring significant preprocessing steps to ensure accuracy and usability. The cleaning process involved:

- **Transforming date variables to usable format:** Ensured that date fields were in a format suitable for analysis.
- **Handling missing values:** Filled or removed entries where necessary to maintain data integrity.
- **Removing outliers in salary data:** Addressed extreme salary values to ensure a more accurate representation of salary trends.

### Analysis Results

The analysis culminated in a comprehensive report created using Power BI. The report includes various visualizations that provide insights into job trends, salary distributions, and application types. Key findings include:

- **Total Job Postings:** The dataset contains a substantial number of job postings, with a breakdown of job types (e.g., Full-time, Contract, Part-time).
- **Salary Insights:** Analysis of maximum, minimum, and median salaries for various positions highlighted salary trends across different job types.
- **Geographical Distribution:** A map visualization illustrated where job postings were most concentrated.

### Project Files

The project directory contains the following files:

- **project1Report.pdf:** A PDF report generated from Power BI, summarizing the key findings and visualizations.
- **Project1notebook.ipynb:** The Jupyter Notebook used for data cleaning, analysis, and visualization.
- **Project1notebook.html:** An HTML version of the Jupyter Notebook for easier viewing in web browsers.
- **data:** A folder containing the cleaned data and any intermediate datasets used during analysis.
- **dump.zip:** The SQL dump of the cleaned database.

### Future Work

Future work for this project could involve classifying job descriptions and titles using machine learning techniques. One possible approach is to implement DistilBERT, a lightweight transformer model, to classify job titles and descriptions based on their content. This classification could provide deeper insights into job trends and requirements.

## Conclusion

This project serves as an extensive analysis of job postings from LinkedIn, offering valuable insights into employment trends. The comprehensive data cleaning and visualization processes have laid a solid foundation for future analysis, including potential classification tasks.
