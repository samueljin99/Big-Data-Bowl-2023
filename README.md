# Big-Data-Bowl-2023
This is the code for my 2023 Big Data Bowl Project. The submission can be found here: https://www.kaggle.com/code/samueljin99/one-spin-to-win-them-all.

I leveraged player tracking data from the 2023 NFL Big Data Bowl competition to develop a framework that identifies spin moves, one prominent type of rushing technique.
Using this identification system, I then trained a gradient boosting model to evaluate spin move rushers and analyze the factors that affect the efficacy of a spin move.
The work also creates a spin move rushing metric to quantify the ability of each rusher to execute a spin move. The statistical properties of this metric are demonstrated.

I used Python to clean and wrangle the data, and to fit it to my physics model. I used R to create visualizations to complement my analysis.
To reproduce my BDB project:
1. First, run the bdb-data-cleaning file and download the output
2. Then, run the bdb_spin_moves_identification file
3. Lastly, run the bdb-model-spin-moves-analysis file
4. Reproduce graphs with the bdb-graphs-making file
