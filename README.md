# Imo-State-Basic-Schools-Viz-Dashboard

<H1>PROJECT OBJECTIVES</H1>
To prepare a viz dashboard for Imo State Basic school data to show:
i. counts and average of basic schools per local government area in Imo state;
ii. towns with the high number of basic schools
iii. Private versus public schools in the state, local governments and town;
iv. counts and average of basic school types in the state, local governments and town; and,
v. counts and average of basic school categories in the state, local governments and town.

<H1>DATA COLLECTION</H1>
The data used for this project was collected from http://www.fmebasic.intellisys.xyz/index.php/states-stats/imo/38-states/imo/155-imo-basic-schools-list. The data type downloaded was Excel File (new format xlsx). The dataset is attached in this repos.

<H1>DATA CLEANING</H1>
The following cleaning was done on the dataset to make it ready for analysis:
<p>1. Duplicates: Following standard practice, I attempted to removed duplicates from the dataset. There were no duplicates in the data. </p>
<p>2. Removing blanks and missing values; as well as data standardisation.</p>
<p>2a. I found and replaced "0" with "O" in Column C which had the institution name. I selected the column so that the replacement did not affected the Column B which had Code (with numeric data).</p>
<p>2c. A lot of cleaning was done on Column D which Town names. First, the Town names were standardised. Example "Works Layout" and "Works Layout, Owerri" are the same. So, one entry was used. The same thing applied to "World Bank". Also, I deleted the entries that has the town names as "Town" and "Village". I deleted the rows that had numeric data in the town name. Also, I removed unnecessary puntuation from `UMUORIEUBI. Next, I found and replaced "0" with "O" in Column C which had the institution name. </p>
<p>With this everything to me is fine and we are ready for the analysis.</p>

