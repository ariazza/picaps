# Python notebooks to analyze data from the PICAPS project (CIAI-Onlus)
Includes notebooks for: cleaning data, visualizing data, classifying data with a decision tree classifier 

The procedure to perform the full analysis is as follows:

1. In order not to have errors, create in your local directory two directories named: output_files/ and output_figures/; all files and figures produced during the run of the code are stored in these two directories. 
1. Run the clean_data.ipynb using the data.csv as input file. This will produce in the same directory an output file at the end, data_clean.csv, which is a clean, transformed and integrated version of the original dataset.
1. Run the visualize_data.ipynb with data_clean.csv as input file.
1. Run the classify_predict_data.ipynb with data_clean.csv as input file.

Run notebooks using Jupyter. 

For info write to dev@gnucoop.com
