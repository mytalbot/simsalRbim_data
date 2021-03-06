# Example data
This repository contains example data from various preference tests that can be analysed in the simsalRbim package. 
In total, there are 6 data sets with quantitative and binary outcomes from the preference tests.
Further, we provide data with different valence ranges. 

The following data can be found in this folder
  * Human_LargeValence_2018 (binary)
  * Human_LargeValence_2017 (binary)
  * Human_LowValence_2017 (binary)
  * Mice_LowValence (quantitative)
  * Mice_LargeValence (quantitative)
  * Monkey_LargeValence (quantitative)

The data can be loaded (as text files) with the bimload function from the R simsalRbim package.   
You might have to download the files into a folder on your computer.  

The package can be found here: [simsalRbim](https://talbotsr.com/simsalRbim/)  

## Loading the data
library(simsalRbim)  
dat <- bimload("YOUR_PATH/Human_LargeValence_2018.txt")  

## Citation and terms of use
The data are presented in the manuscript **"place title here"** which is currently under review.  
You may use the data for scientific purposes only.   
Please cite the paper when the data are used.  

Enjoy!
