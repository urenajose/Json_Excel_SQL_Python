# Json_Execl_SQL_Python
Created a Google Colab Notebook which:

Reads a json file with pandas and exports/coverts to SQL file and several Excel files.
> json file named dummy_data.json contains dummy data which was randomly generated
> the dataset has (Rows 8000, Column/Features 12)

>Notebook:
"https://colab.research.google.com/drive/1BU9d0VYbBLJg-b-iT1W04lU7au50N-WU?usp=sharing"

### Dataset columns/features
```
 #   Column       Non-Null Count  Dtype         
---  ------       --------------  -----         
 0   First Name   8000 non-null   object        
 1   Last Name    8000 non-null   object        
 2   Race_Origin  8000 non-null   object        
 3   State        8000 non-null   object        
 4   Code         8000 non-null   object        
 5   Amount       8000 non-null   float64       
 6   Age          8000 non-null   int64         
 7   Date         8000 non-null   datetime64[ns]
 8   Contacted    8000 non-null   int64         
 9   Year         8000 non-null   int64         
 10  Month        8000 non-null   int64         
 11  Sex          8000 non-null   object    
```
The notebook reads the json file located within this repo.

### Column State is rename to State/Territory

### Extra columns/features are added to ehance the dataset for better exploration:
  
* Census Regions
* Age group

### The Notebook inclues several exploratory and analytical steps:

* Mean, Stand divisiasion, min, max, 
* Count of significant statiscal categorical data such as Biological Sex, Race
* Plot/Graph Dinsity, Histogram, Box and Whisker, pairwise relationships  of certain features

### Save dataset as a SQL .db file and create individidual excel files named:
  ["NorthEast","Midwest","South","West","Puerto Rico","U.S. Territory"] 

Also a file named All_DummyData.xlsx is save as well, with all the data in a single sheet.

### Excel file with graphs, tables, pivot tables, and formulas can be downloaded:

https://github.com/urenajose/Json_Excel_SQL_Python/blob/main/excel_data_exploration.xlsx?raw=true


