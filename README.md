# Franck-Hertz Experimental Data Analysis
Python program written in Jupyter Notebook to analyze experimental data obtained from a Franck-Hertz experiment at temperatures of 130°C, 140°C, and 150°C. 

## FH_Graphs.ipynb
The program utilizes LOWESS smoothing, Savitzky–Golay filtering, manual peak and dip identification, quadratic curve fitting, linear curve fitting, and covariance-based parameter uncertainty estimation to determine the excitation energy ($E_a$), mean free path ($\lambda$), and offset energy ($E'$).

## Dependencies
- NumPy
- pandas
- Matplotlib
- SciPy
- statsmodels
