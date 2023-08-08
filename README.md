#Discharge Data Analysis and Modeling
This repository contains a Python script to analyze and model annual maximum discharge data.

Purpose
The code is designed to:

Read a dataset with daily discharge measurements.
Extract the maximum discharge value for each year.
Model the annual maximums using various statistical methods, notably the LogPearson method.
Visualize the data and the modeling results.
Dependencies
Prerequisites:
Python
Libraries: pandas, numpy, matplotlib, scipy, re, and os.
To install the necessary libraries, use the following:

bash
Copy code
pip install pandas numpy matplotlib scipy
Dataset
Structure:
The dataset (caonillas.txt) is expected to have:

Date: A date in a recognizable format.
Value: Daily discharge measurements.
Instructions to Run
Setup: Clone this repository to your local machine.
Data Placement: Ensure the dataset caonillas.txt is in the root directory of the cloned repository.
Execution: Navigate to the directory containing the script in a terminal or command prompt. Run the script using the command:
bash
Copy code
python script_name.py
Replace script_name.py with the actual filename of the Python script.

Visualization: The script processes and visualizes the data, presenting two plots:
A scatter plot showcasing return years vs. maximum yearly discharge values.
A line plot comparing the real maximum yearly discharge values with the LogPearson modeled values.
Output
On successful execution:

You'll first see a scatter plot of return years against the maximum yearly discharge values.
Subsequently, a visualization of the actual maximum yearly discharge values juxtaposed with the LogPearson modeled values will be displayed.
