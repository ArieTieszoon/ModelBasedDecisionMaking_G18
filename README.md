# EPA1361-Flood risk Ijsel - Modeling under deep uncertainty for the municipality of Deventer

This repository is made for the EPA course Model Based Decision-making. 

- Notebook Open exploration experiment runs: Runs experiments with given model using the the given uncertainties and problem formulation to (1000 scenarios 100 policies).

- Notebook Open_exploration: Takes the different experiments and outcomes from previous notebook and compares A.5 with A.4, and A.5 with all other regions. 
                           Also an random trees, extra trees algorithm was run to find the sensitivities the model to all uncertainties.

- Notebooks Processing_basecase: These notebooks alter the dataframes that are put out by the 'Open exploration experiment runs' to fit into the Prim notebooks

- NotebookS Prim and dimensional stacking: These notebooks look into what factors in the model result in certain outcomes. This is done in the basecase, 100 random policies and the advised policies. 

- Notebook Multi-Scenario MORDM: This notebook Select scenarios to run the MORDM on. The run itself is also included here.

- Notebook Robust_best_worst: This notebook aims to test policies found by MORDM on their robustness and outputs policies that work best under both the minimax regret and maximin cases.

These notbook resulted to the figures and outcomes folder.

All the other files are provided by the EPA1361 course team and can be found here: https://github.com/quaquel/epa1361_open/tree/master/final%20assignment  