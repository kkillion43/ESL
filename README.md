# Homework Week 12 - ESL percentage by state
Kyle Killion
July 31, 2016

<hr>

#### What to accomplish:

1. Download *dataset1.sas7bdat* from 'Files' class archive
2. Read in Data via SAS and Export DataSet in xlsx format
3. Insert assigned data of ESL percentage by State (English Second Lang)
4. Attach to Github and submit link


<hr>
#### SAS University Edition
*Uploaded dataset1 to myfolder and pointed reference to libname myfolders
```
libname myfolder '/folders/myfolders/';

proc export
data= myfolder.dataset1
outfile='/folders/myfolders/Data/States.xlsx'
dbms=xlsx
REPLACE;
run;
```
<hr>

####Included ESL_Percentage

Inserted the *ESL_Percentage* data within the entire data set

<hr>
####States with ESL_Percentage File

Click Here for file [![click Here](images/Hoosiers.png)](https://github.com/kkillion43/ESL/blob/master/ESLbyState.xlsx?raw=true)
