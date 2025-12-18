Repository for my final projec in Stats-503

Contents:

Scripts: 
Contains two analyses 
1) Visualizing decoding data derived from an MEG experiment, and apply Bayesian tests to it over time + conduct a bootstrapping test.
2) Visualize decoding data using a temporal generalization matrix, and apply Bayesian tests to the matrix.

Data:
All of the relevant data for the experiment. S0X_DecodingAccuracyTimecourse has the per participant decoding scores,
S0Xtraintime_data contains the scores for the temporal generalization matrix,
BF_matrix contains the saved BF score data across the temporal generalization matrix

Environment:
Contains the necessary environment file for installing the packages in python to run the analyses

Times:
Contains a file with the experiment times that is loaded in for plotting

Steps for reproducibility
1) Use a code editor that can open .ipynb files
2) Install both R and python
3) Use project_environment.yml to install the necessary packages (note: I use a Silicon mac. This may need adjusting for other operating systems)
4) Clone the directory, and set 'top_dir' in the scripts to the path for the directory.
5) Set the path to your r directory in the script -> ro.r(your/path/here)
