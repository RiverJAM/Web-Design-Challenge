# Web-Design-Challenge

This repo is an excercise in html, css, bootstrap and a little bit of Pandas for making an HTML table from a .csv.

The index.html is the coding for the landing page. Much of the code for each page originated here: The navigation bar at the top, the visualization links, and the general look of the site.

style.css is the file containing much of the style  for the site overal. It also has unique IDs and classes for object in the code.It is also contains media queries marked by the @ symbol to facilitate changes in window size.

The assets folder contains the png files for each data visualization that is called up in the html repeatedly. These files were copied from the assignment

cities.csv is the original data in csv form. newnu is the jupyter workbook with the python code (Pandas) used to turn the csv into
html (data.html) for the table on the datapage.html page

datapage.html is the data page displaying all the underlying data for the scatter plots. It is a table generated from pandas into html
then into a bootstrap table. Striped to match the style of the screenshot from the assignment.

viz1.html, viz2.html, viz3.html, and viz4.html are all analysis pages displaying the plots in detail. Being that there is one central container, the data takes up more space in the window and is easier to read.

The Resources and visualizations folders were not used.