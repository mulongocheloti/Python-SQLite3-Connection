# Database programming
---
<b>TASK:</b> 
*    Create a database instance, table and insert records into the table<br>
<B>NOTE:</B>   <i>The record values for the table are to be retrieved from a csv file in the zip file <a href="https://github.com/mulongocheloti/Python-SQLite3-Connection/blob/main/data.rar">data.rar<a></i>
---
<b>SOLUTION:</b>Done in Google Colab<br>
Steps Involved;<br>
1. Download the ([zip](https://github.com/mulongocheloti/Python-SQLite3-Connection/raw/main/data.rar)) file, unzip and copy .csv file into your working directory. Read it in.<br>
   Interested in only two fields; **'Countries'** and **'2017 vs 1990: change(%)'**<br>
   Do any relevant transformations.<br>
  
2. Using SQL,
*   Create a database instance.
*   Create a table named **Emmission** with two fields  named **country** and **%_change(1990-2017)**
*   From the selected columns, Insert relevant records into the two fields of the table Emmission and save the changes.
*   Sort the table; with the country with the highest %_change(1990-2017) on top.
<br>
  
3. Display only the top 10 countries.<br>
  
4. Plot a graph.
<br>
 The clip below shows the steps and code running;<br><br>

https://user-images.githubusercontent.com/68067031/175557483-6be8fa12-f1a7-441d-8bfd-2bb8e15cc81a.mp4

