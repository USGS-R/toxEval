# toxEval

Initial code for studying ToxCast data in relation to measured concentrations.

Disclaimer
----------
This software is in the public domain because it contains materials that originally came from the U.S. Geological Survey  (USGS), an agency of the United States Department of Interior. For more information, see the official USGS copyright policy at [http://www.usgs.gov/visual-id/credit_usgs.html#copyright](http://www.usgs.gov/visual-id/credit_usgs.html#copyright)

Although this software program has been used by the USGS, no warranty, expressed or implied, is made by the USGS or the U.S. Government as to the accuracy and functioning of the program and related program material nor shall the fact of distribution constitute any such warranty, and no responsibility is assumed by the USGS in connection therewith.

This software is provided "AS IS."

Package Installation
---------------------------------

To install the `toxEval` package you need to be using R 3.0 or greater. Then use the following command:

```R
install.packages(c("devtools","shiny","dplyr","ggplot2",
                   "tidyr","stringi","data.table","grid","gridExtra"))
library(devtools)
install_github("USGS-R/toxEval")
install_github("rstudio/DT")
install_github('rstudio/leaflet')

library(toxEval)
library(shiny)
pathToApp <- system.file("shiny", package="toxEval")
runApp(pathToApp)

```

Linux: [![travis](https://api.travis-ci.org/USGS-R/toxEval.svg?branch=master)](https://travis-ci.org/USGS-R/toxEval)


 [
   ![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)
 ](http://creativecommons.org/publicdomain/zero/1.0/)
