# python_course
This repository contains the final project for the Python course taught by Luigi Petrucco at CIMeC.

The purpose of the project is to load tabular data from Excel files, organize them in appropriate `pandas` dataframes, and draw plots for data inspection and dissemination. To this end, I prepared two notebooks:

- `Boxplot_OT.ipynb` draws boxplots for all the experimental conditions contained in input data files, then writes them to disk
- `Linegraphs.ipynb` draws lineplots for all the experimental conditions contained in input data files, then writes them to disk

Input data files are contained in folder `Data`.

Both notebooks depend only on `os`, `pandas`, `matplotlib.pyplot`, and `seaborn`. 


