# Analysis-Of-Supply-Chain-Disruption

**Team members**

 1. Aswin Prasad  
 2. Farha Kauser
 3. Jayasurya Pinaki
 4. Shubhangi Yadav

**Data Source**
<http://www.fao.org/faostat/en/#home>
<https://quickstats.nass.usda.gov/>
<https://public.emdat.be/>

**Run bulk insertion script for data from csv to mongoDB**
Place csv file into supply-chain-disruption-analysis\backend\src\scripts\datasets folder
Go to supply-chain-disruption-analysis\backend\src\scripts folder and run following command:

node bulkInsertionFromCsvToDB.js sample.csv  

sample.csv is a command line argument for the filename that needs to be used.
