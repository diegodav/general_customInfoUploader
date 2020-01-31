# general_customInfoUploader

### This script takes as input a CSV file with the following characteristics:
### 1. No Protected Health Information (PHI) in the file
### 2. All columns are named
### 3. The first column is subejct ID (bblid)
### 4. All data is numeric (i.e. 1s and 0s) \n
#
### It then organizes the data into dictionaries, and uploads it to each subject's Custom Info field on flywheel. \n
#
#
### The script can be called in the terminal by doing: ```python customInfoUploader.py -d path/to/CSV -p name_of_project -n dict_name``` \n 
#
### *NOTE: Prior to uploading, please sign into a flywheel session in your environment. See here for instructions: https://flywheel-io.github.io/core/branches/master/python/getting_started.html
