## ml_in_freshwater_management
#### This repository holds the relevant files for AISC Freshwater Management: ((https://community.ai.science/ml-in-freshwater-management))

 The notebooks herein were designed as instruction tools for use in the 12 week long working group sponsored by NRCan. 
 
 + The 'Data' folder has the raw satellite readings for Canada's great nothern lakes, as well as the estimated error recordings for Lake Winnipeg. 
 
 + The 'winnipeg_error_raw' Jupyter Notebook file shows how to process the satellite readings to find the error in the measurements. 
 
 + The 'kf_numpy' and 'kf_numpy_2' Jupyter Notebook files are machine learning free means of building a Kalman Filter in python. 
 
 
 + A random forest regression -hybrid- Kalman Filter, that injects itself every X time steps to maintain filter confidence. This hybrid model's effectiveness is tied to the size of the amplitudes of error (& uncertainty). 

