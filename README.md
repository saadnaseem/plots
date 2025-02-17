# plots
code for plots relevant to a biology lab 



# (a)                Volcano Plot for Proteomics Data

This repository contains code to create a volcano plot from proteomics data. The plot compares Sample A vs. Sample B to show the differential expression of proteins between the two conditions.

https://pubs.rsc.org/en/content/articlelanding/2020/mo/d0mo00087f
Guide for protein fold change and p-value calculation for non-experts in proteomics, 

Overview
	•	What It Does:
Generates a volcano plot. One quadrant shows proteins that are up-regulated, and another shows proteins that are down-regulated between the two conditions.
	•	Background:
 
In proteomics, volcano plots help visualize changes in protein expression.
	•	X-axis: Log2 fold change (difference between conditions)
	•	Y-axis: -log10(p-value) (statistical significance)
 
This plot type is common in differential expression analysis.

	•	Provided Data:
 
A dummy Excel file is included to run the notebook and test the code. 
(2_sampleA_sampleB.xlsx)

How to Use
	1.	Clone the Repository:

git clone https://github.com/saadnaseem/plots.git

	2.	Open the Notebook:
Use Jupyter Notebook or Google Colab.

	3.	Run the Code:
Load the dummy Excel file and execute the notebook to see the volcano plot.

Who Should Care
	•	Biologists & Bioinformaticians:
Easily visualize differential protein expression.
	•	Metabolic Engineers & Genomics Researchers:
Quickly assess changes in protein levels between conditions.

Requirements
	•	Python 3.x
	•	Required libraries: pandas, numpy, plotly, etc.
