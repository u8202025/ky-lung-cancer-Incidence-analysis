# Project Plan: Analysis of Lung Cancer Incidence, Tobacco Usage, and Radon Levels in Kentucky Counties

## Introduction
In July 2020, my mother passed away in Taiwan due to lung cancer. She did not smoke, nor was she exposed to smoking environments or significant cooking fumes. Doctors attributed the primary cause of the disease to genetic mutations. However, research experts indicate that even with genetic mutations, external carcinogenic factors exist, including smoking, secondhand smoke, vehicle emissions, PM 2.5, cooking fumes, as well as preservatives and food additives in food.

While verifying various statistical data, I unexpectedly discovered that the state of Kentucky has the highest cancer and lung cancer rates in the United States. Therefore, I intend to analyze the incidence rates (per population) of cancer and the contributing factors - adult smoking rates and indoor Radon levels - across counties in Kentucky to assess their correlations. After searching databases and conducting data clearing and analysis, my spouse (with a programming background) performed detailed programming tasks to complete this report. Our aim is to raise awareness of lung cancer and its importance.

## Project Overview
- This project aims to analyze lung cancer incidence rates in Kentucky counties, comparing the top ten most populated counties (out of 120 counties) with the highest incidence rates. Additionally, we examined radon levels and adult tobacco usage rates in these counties to explore potential correlations with lung cancer incidence.
- To visualize the correlation, we plot bar charts for each variation and combine the data in a 3D plot.

## Technical Insight
- **Data Sources:** Three main databases were used in this project:
  - 1st data: Incidence Rate Report for Kentucky by County Lung & Bronchus (All Stages), 2016-2020 All Races (includes Hispanic), Both Sexes, All Ages Sorted by Rate 
    (https://statecancerprofiles.cancer.gov/incidencerates/)
  - 2nd data: EPA Map of Radon Zones and Supplemental Information.(https://www.epa.gov/radon/epa-map-radon-zones-and-supplemental-information#datainfo) 
  - 3rd data: Adult Smoking Prevalence by County, Kentucky, 2013-2017.(https://kyibis.mc.uky.edu/ehl/dataportal/indicator/view/TobaccoSmokeAdult.Cnty.html)
- **Tools and Technologies:** Python programming language for data manipulation and analysis, libraries such as pandas, numpy, and matplotlib for data visualization. VS Code, Python, and Jupyter Notebook.
- **Methodology and Visual Aids:** The complete process of accessing and requesting databases, cleaning and sorting data, statistics for populations, radon index, and percentage of smokers by county were listed in order in the file of Final_project.ipynb.

## Code Kentucky Feature Lists
- **Feature list #1 choice:** Utilized pandas to read multiple data files (json, csv, xls, etc.) from websites.
- **Feature list #2 choice:** Clean, sort each data, and create data frames for lung cancer incidence rates, radon levels, and adults tobacco usage rates.
- **Feature list #3 choice:** Plot bar charts using matplotlib.
- **Feature list #4 choice:** Instructions for setting Python virtual environment.
- **Feature list #5 choice:** Annotate codes in Jupyter Notebook, write clear code comments, and have a well-written README.md.

## Setting up a Python Virtual Environment
A Python virtual environment is a self-contained directory that contains a Python installation for a specific project. Using virtual environments helps manage dependencies and isolate project-specific packages. Here's how to set up a Python virtual environment:

### Prerequisites
- Make sure you have Python installed on your system. If not, download and install it from [python.org](https://www.python.org/).

### Instructions

1. **Open a Terminal/Command Prompt**

    - On Windows, you can use Command Prompt or PowerShell.
    - On Unix-based systems (Linux, macOS), use the terminal.

2. **Navigate to Your Project Directory**

    ```bash
    cd path/to/your/project
    ```

3. **Create a Virtual Environment**

    ```bash
    python -m venv venv
    ```

    This command creates a virtual environment named 'venv' in your project directory.

4. **Activate the Virtual Environment**

    - On Windows (Command Prompt):

        ```bash
        venv\Scripts\activate
        ```

    - On Windows (PowerShell):

        ```bash
        .\venv\Scripts\Activate
        ```

    - On Unix-based systems:

        ```bash
        source venv/bin/activate
        ```

    After activation, your terminal prompt should change, indicating that the virtual environment is active.

5. **Install Dependencies**

    Now that the virtual environment is active, you can install project-specific dependencies without affecting the global Python installation.

    ```bash
    pip install -r requirements.txt
    ```

    Replace `requirements.txt` with the actual name of your requirements file.

6. **Deactivate the Virtual Environment**

    When you're done working on your project, deactivate the virtual environment.

    ```bash
    deactivate
    ```

## Conclusion
By incorporating the lung cancer incidence rates, three radon levels alongside with tobacco usage rates in most populated counties, we merged the three data sets in a table and displayed it as a 3D plot. This project plan tried to offer a holistic approach to examine potential environmental and behavioral factors that can influence lung cancer incidence in Kentucky.

