# Flight Difficulty Score - United Airlines SkyHack 2.0

## Project Overview

This project addresses the operational challenge of identifying high-difficulty flights at Chicago O'Hare International Airport (ORD). Currently, this process relies on experience and manual assessment, which is inconsistent and not scalable. This solution introduces a data-driven **Flight Difficulty Score** that systematically quantifies the complexity of each flight, enabling proactive resource planning and improved on-time performance.

The analysis uses five datasets spanning two weeks of departures from ORD, covering flight schedules, passenger loads, baggage information, and special service requests. The final output is a daily-ranked list of flights, categorized as "Easy," "Medium," or "Difficult."

## Files in this Submission

1.  **`presentation.pdf`**: The main report and presentation deck summarizing the project's methodology, findings, and recommendations.
2.  **`Pairadox.csv`**: The required output file containing the final difficulty score and class for each flight.
3.  **`main.ipynb`**: The complete Jupyter Notebook containing the Python code for data processing, feature engineering, and score calculation.
4.  **`requirements.txt`**: A list of the required Python libraries to run the notebook.
5.  **`README.md`**: This file.

## Setup and Instructions to Run

### Requirements

This project requires Python 3.x and the libraries listed in the `requirements.txt` file.

### Steps to Run

1.  **Create a Virtual Environment (Recommended)**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

2.  **Install Required Libraries**:
    Navigate to the project folder in your terminal and run the following command to install all necessary packages:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the Notebook**:
    Open the `analysis.ipynb` file in Jupyter Notebook or JupyterLab. To generate all outputs and the final `test_yash.csv` file, run all cells in order by selecting **Kernel > Restart & Run All** from the top menu.
