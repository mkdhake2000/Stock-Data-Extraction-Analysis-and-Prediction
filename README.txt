**USING PYTHON 3.9.6 IS RECOMMENDED**
**INSTALL JUPYTER NOTEBOOK**
**KINDLY RE-RUN THE ENTIRE NOTEBOOK IF YOU FACE DIFFICULTIES, ALL AT ONCE UNLIKE CELL BY CELL EXECUTION, BECAUSE RUNNING A CELL TWICE AT
SOME POINT OF TIME MAY CAUSE INCONSISTENCIES**
**FOR MORE SPECIFIC INFORMATION OF ANY PART,PLEASE REFER THE COMMENTS IN THAT PARTS ipynb FILE**


REQUIREMENTS:
You are requested to install below packages before executing scripts
	1.numpy
	2.pandas
	3.sklearn
	4.matplotlib
	5.seaborn
	6.datetime
	7.keras
	8.selenium
	9.time
	10.tensorflow

ORDER OF EXECTUTION:(there exists dependencies between the notebooks)
1.run 'ScrapeStockData.ipynb'

   ->input:No input required(only website "https://www.tickertape.in/screener" needs to be functioning properly and "chromedriver.exe" for the current chrome version(here chromedriver for chrom v96 is used) should be present in same folder to connect to chrome using webdriver)

   ->output: stock-data.csv

2.run 'StockDataProcessing.ipynb'

   ->input:stock-data.csv

   ->output:large-cap.csv, medium-cap.csv, small-cap.csv, top-6-large-cap.csv

3.run 'ScrapeCompanyData.ipynb'

   ->input:No input required(only website "https://finance.yahoo.com/" needs to be functioning properly and "chromedriver.exe" for the current chrome version(here chromedriver for chrom v96 is used) should be present in same folder to connect to chrome using webdriver)

   ->output:LTI.csv,MINDTREE.csv,ASTRAL.csv,DEEPAKNTR.csv,PERSISTENT.csv,NAUKRI.csv,
           VENKEYS.csv,TATASTLLP.csv,JKTYRE.csv,RAYMOND.csv,TATAMETALI.csv,TCS.csv,
           COGNIZANT.csv,INFOSYS.csv,HCL.csv,WIPRO.csv,ONGC.csv,RAJESHEXPORTS.csv,
           ICICI.csv,HDFC.csv,NIFTY.csv,NIFTY 50_Data.csv,MINDTREE-PREDICTION.csv

4.now run 'Stock Analysis and Prediction.ipynb'

   ->input:LTI.csv,MINDTREE.csv,ASTRAL.csv,DEEPAKNTR.csv,PERSISTENT.csv,NAUKRI.csv,
           VENKEYS.csv,TATASTLLP.csv,JKTYRE.csv,RAYMOND.csv,TATAMETALI.csv,TCS.csv,
           COGNIZANT.csv,INFOSYS.csv,HCL.csv,WIPRO.csv,ONGC.csv,RAJESHEXPORTS.csv,
           ICICI.csv,HDFC.csv,NIFTY.csv,NIFTY 50_Data.csv,MINDTREE-PREDICTION.csv
           
   ->does not return any output files
   
   ->for more information you can refer to the comments  the python notebook 