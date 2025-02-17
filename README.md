# plots
code for plots relevant to a biology lab; a) volcano plot, b) growth curve  



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




#  (b) Growth Curves Plotting Script

This repository contains the `growthcurves_github` script to generate **growth curves** from experimental data. The **x-axis** represents **time**, and the **y-axis** represents **absorbance** (OD600). 

## 📌 Overview
In biological experiments, measurements are often taken in **triplicates** to ensure accuracy. This script:
- **Averages** the triplicate values.
- **Calculates the standard deviation** to show variability.
- **Plots the growth curves** with error bars.

## 📂 Files in this Repository
- **`growthcurves_github.py`** – Python script to process and visualize growth curves.
- **`data_growthcurve.xlsx`** – Dummy data file for testing the script.

## 🔧 Installation & Requirements
Ensure you have Python installed along with the required libraries:

```bash
pip install pandas matplotlib openpyxl

🚀 How to Use
	1.	Prepare Your Data
	•	Your data should be in an Excel file (.xlsx format).
	•	The first column should be time.
	•	The next columns should be absorbance values for different wells.
	2.	Run the Script

python growthcurves_github.py


	3.	Output
	•	A growth curve plot with error bars will be generated.
	•	The x-axis represents time (hours).
	•	The y-axis represents absorbance (OD600).

📊 Example Data Format (data_growthcurve.xlsx)

Time (hrs)	A1	A2	A3	B1	B2	B3	…
0.0	0.1	0.1	0.1	0.1	0.1	0.1	…
1.0	0.2	0.2	0.2	0.2	0.2	0.2	…
2.0	0.3	0.3	0.3	0.3	0.3	0.3	…

📜 License

This project is licensed under the MIT License.

💡 Author

Created by Saad Naseem
