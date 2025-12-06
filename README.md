# Chem-274B-Micropresentation
This project will use graph-based analysis to find correlations between different drugs and their side effects they cause. Using Networkx, we use a myriad of algorithms to analyze the data. 

## How to Run
As long as each cell runs, you all the dependencies should work just fine. There is, however, a requirements.txt file if needed.

The dataset is too big to upload in the repository so you must download it from this link: https://snap.stanford.edu/biodata/datasets/10017/10017-ChChSe-Decagon.html. However, the program can work with just the sample.csv file.

You must open the micropresentation.ipynb jupyter notebook file to run the program. Our group worked on google collabs. You must put the datasets `ChChSe-Decagon_polypharmacy.csv` and `sample.csv ` in the same folder as the project you are running the jupyter notebook so that you can run it. Within the file, you can run each cell in order. 

Currently, the program uses the sample.csv file as to not have too long of a runtime. However, you can change this to use the full file (with 4 million data points) by changing the 41st line from: 

`for _, row in sample.iterrows():` to `for _, row in df.iterrows():`



