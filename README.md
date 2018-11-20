# humanrights
Analyzing tone of human rights events from GDELT, 
purpose : analyze whether human rights events would affect status of country (developing/developed)

Data is acquired from GDELT using Google bigquery then saved as csv file and processed
TIME : 2018
DATA :
- Demo about human rights (Event Code : 1413)
- Accusing of Human Rights abuses (Event Code : 1122)
- Investigation of Human Rights abuses (Event Code : 092)
- Demand Rights (Event Code : 1043 )
- Reject Request Rights (Event Code : 1233)

PROCESS :
1. opening data from GDELT using google big query, filter data using SQL query, save to csv
2. Pre-processing
3. Desribe data using statistics
4. Machine Learning
5. Evaluation

Contain of:
1. Data acquired : demoHR, accuseHR, investigationHR
2. Data preprocessing : demoData, accuseData, investigationData

3. Code for pre-processing : 
              - "DataDemandRights - 1043.ipynb" 
              - "DataRejectRequestRights - 1233.ipynb"
              - "Dataaccuse - 1122.ipynb"
              - "Datademo - 1413.ipynb"
              - "Datainvestigation - 92.ipynb"
              
4. Code for Stat Descriptive  
             - "proyek.ipynb" : tone analysis
             - "MergeData.ipynb" : statistic descriptive + add data
             
5. Code for ML ======on going=========
6. Eval code =====on going============

