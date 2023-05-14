# DiplomaHSE
Comparative Analysis of Recommendation Models Based on Purchase Data in E-commerce

Stepanov212_VKR.ipynb - the module that performs the following:
preprocessing data from an electronika_03_04_col.xlsx file, including using the citylst.xlsx dictionary of regions,
creating the VKR.xlsx file and writing aggregated data to it according to various criteria after preprocessing,
creating a customer showcase using aggregation of source data,
writing to the VKR.xlsx file summary information about the customer showcase,
clustering and checking its quality,
writing to the VKR.xlsx file summary information about various clusters,
creating NCF.xlsx, ratings.xlsx , mba.xlsx files with a customer showcase divided into clusters and brought to the appropriate format

Stepanov_NCF.ipynb - the module implementing the NCF machine learning method using the ncf.xlsx source file and intermediate test.csv and train.csv files

Stepanov_SVD.ipynb - the module implementing the SVD machine learning method using the ratings.xlsx source file

Stepanov_MBA.ipynb - the module implementing the MBA machine learning method using the mba.xlsx source file

VKR.xlsx - the file containing characteristic information about the initial preprocessed data, the customer showcase and the division into clusters

VKR_analysis.xlsx - the VKR.xlsx file processed to a suitable appearance with color sorting and analytical diagrams

citylst.xlsx - list of cities corresponding to regions
