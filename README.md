# sapmuebase

sapmuebase is a package with simple functions usefull in the SAP MUE team.

## Install
With `devtools` package installed:
```
library(devtools)
install_github("Eucrow/sapmuebase")
```

## Functions available (use help(*nameofthefunction*) to details):
### importCsvSAPMUE()
Import csv files with special format usually used in SAPMUE team.
### exportCsvSAPMUE()
Export csv files with special format usually used in SAPMUE team.
### importMuestreosUP()
Import the 'muestreos tallas por up' files from SIRENO to R. 
### importIPDFile()
Import the file with data to dump in SIRENO to R.
### exportListToCsv()
Create a csv file for each dataframe in a list of dataframes.
### separateDataframeByInfluenceArea()
This function separate a dataframe by influence area.
### humanize()
Create new variables with description values from coded variables.
### addInfluenceAreaVariable()
Add an influence area variable.
