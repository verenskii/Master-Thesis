# Protein Folding Modelling (SPN)
Protein folding simulations were performed using the developed Stochastic Petri Net (SPN) model by systematically varying the mass-action parameters of the translation reaction (1-10) and the ATP source (0.1-10). Different combinations of both parameters were investigated to evaluate their influence on protein folding and the dynamics of individual model components. The simulations were carried out for either 500, 1500 or 10000 simulation steps and repeated ten times to account for the stochastic nature of the model. U according to different mass action paramters used in creating the datanless otherwise stated, results are presented as the mean $\pm$ standard deviation of the ten simulation runs.

## Files
| Filename | Type | Content | 
|---|---|---|
| `thesis_graphs.ipynb` | Jupyter Notebook (Python) | Loads selected thesis data and generates figures with consistent formatting suitable for inclusion in the thesis. |
| `looooong.ipynb` | Jupyter Notebook (Python) | Imports data from CSV files, calculates means and standard deviations, generates preliminary plots, and exports the processed data as DataFrames.
| `looooong` | Directory | Contains the raw data (CSV) used in the `looooong.ipynb` notebook, organized into subdirectories according to the mass-action parameters used during data generation.
| `protein5_ATP8_ATPreaction.ipynb` | Jupyter Notebook (Python) |Imports data from CSV files, calculates means and standard deviations, generates preliminary plots, and exports the processed data as DataFrames.
| `ATP_reactions` | Directory | Contains the raw data (CSV) used in the `protein5_ATP8_ATPreaction.ipynb` notebook, organized into subdirectories according to the mass-action parameters used during data generation.