# How-to-read-text-file-from-directory-in-jupyter-notebook-of-anaconda-solved-
How to read text file from directory in jupyter notebook_of anaconda(Solved problem).

import pandas as pd # used to create and call dataframe! 
# the next code line(df = ....) is correct datapath of my text file. You have to enter your data path/directory correctly. 
# Pls use double backslash(\\) between paths. 
df = pd.read_csv("C:\\Users\\Samuel Bulti Wakgari\\Afaan_Oromoo_POS_tagging\\Input\\samiCorpora.txt")  
df     # with this command you can see your file
