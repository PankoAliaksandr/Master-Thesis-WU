This folder contains:

1) The Source Code file: Aliaksandr_Panko_Master_Thesis_Source_Code
2) The Final Master Thesis .pdr document: Aliaksandr_Panko_Master_Thesis
3) 2 Data files: required_stocks_USA.csv, required_stocks_Europe.csv
4) The dendogram picutre: dendogram

The source code file combines Latex and R code.


To run a source file the next steps are required:

1) R environment (the project is done in R version 3.4.0 (2017-04-21))
2) Latex compiler:
LaTeX can be run directly through RStudio,
so long as you have MikTeX installed on your computer as well
(here’s a link to the MikTex download page: https://miktex.org/2.9/setup). 
3) The next libraries are required for R:
	3.1) library(xts)
	3.2) library(lubridate)
	3.3) library(CLA)
	3.4) library(PerformanceAnalytics)
	3.5) library(xtable)
	3.6) library(graphics)

4) Put required_stocks_USA.csv and required_stocks_Europe.csv files
 under "D:/ESG Results"
5) Put dendogram.png into the same folder as the source code file.

