SEIRD-model-based-Covid-19-simulation

There are two Ipython Notebook files available:
"CPT_591_ABM_SEIRD_with_RIDGE_PREDICTION_VER2.ipynb" and"CPT_S-591_Graph.ipynb"

In "CPT_591_ABM_SEIRD_with_RIDGE_PREDICTION_VER2.ipynb", the code utilizes the "st_99" library to draw a map of the United States and mark the abbreviated state names. it imports COVID-19 epidemic data for all US states, including files named "confirmed_cases.csv", "recovered_case.csv", and "death_cases_csv", Additionally, population data is imported from"pop_age_prop_ver2.csv".The notebook implements an epidemic simulator.

In "CPT_S_591_Graph.ipynb", the code preprocesses air flight information from a file named "". it then stores the processed data in a file called"flight_int_adjaceny_matrix.npy".The notebook builds a graph network and displays important notes within the network.

To use codes, you need to unzip the "" file and download all the required files to your local machine or Google Drive. Adjust the file paths in the code to match the location of the download files. You should first run "CPT_S_591_Graph.ipynb" to generate a new "flight_inf_adjacency_matrix.npy" and create a graph network. Alternatively, you can skip running "CPT_S_591_Graph.ipynb" and use the existing "flight_int_adjacency_matrix.npy" file to directly execute "CPT_591_ABM_SEIRD_with_RIDGE_PREDICTION_VER2.ipynb".

