# Reaction-Time-Analysis
Analysis of auditory vs visual reaction times in Python.

# Reaction Time Analysis - Auditory vs. Visual Stimuli

## Goal
Analyze a publicly available cognitive reaction time dataset to explore differences in how participants respond to auditory versus visual stimuli.

## Research Questions
1. How do reaction times differ between auditory and visual stimuli?
2. What is the variability (standard deviation) in responses?
3. Are there patterns of missing data?

## Tools & Technologies
- Python  
- pandas  
- matplotlib  
- Google Colab

## Method:
1. Loaded the dataset into a pandas DataFrame
2. Removed unnecessary index columns and checked for missing values.
3. Cleaned the dataset by excluding missing reaction times.
4. Calculated mean reaction time and standard deviation for each stimulus.
5. Summarized results in a table and visualized distributions using a boxplot.

## Results

| Stimulus | Mean RT (ms) | SD (ms) |
|---------|-------------|---------|
| Auditory | 215.86 | 86.88 |
| Visual | 288.82 | 60.42 |

## Key Findings
-The participants responded faster to auditory stimuli than to visual stimuli. 
-Auditory responses showed greater variability than visual responses. 

## Visualization
A boxplot is included in the notebook to show the distribution of reaction times for auditory and visual stimuli.

## How to Run
1. Open the notebook in Google Colab
2. Ensure the CSV File is available in the same directory as the notebook.
3. Run the cell to reproduce the analysis, summary table, and visualization.

## Why This Project Matters
Reaction time data is widely used in neuroscience, psychology, human-computer interaction, and AI research. This project demonstrates core scientific programming skills, including data cleaning, statistical analysis, and result communication. Understanding reaction time variability can support research in cognitive science and contribute to the development of AI systems that better adapt to human behavior. 
