### Intro

I was tasked with investigating the relative efficacy of several anti-cancer drugs in a longitudinal rodent study. I used Pandas, Numpy, and Matplotlib in a jupyter notebook running Python 3.

### Method & Results

Initially, I was given two csv datasets, which I merged. The resulting dataframe had unique Mouse ID keys, with the rest of the columns producing data that repeated vertically. 
To produce a line plot for each drug of interest, along with error bars at each time point, I needed to groupby the drug name and timepoint, saving the means. The errorbars were computed on the fly during the plotting itself. This process was repeated for each DV of interest.
Additionally, I was tasked with creating a somewhat bespoke bar chart, which required converting the relevant percent changes to a tuple.
Please see the .ipynb file for additional details.
