# Pewlett_Hackard_Analysis

### Overview of analysis
  The purpose of this analysis was to use 6 different csv files to manipulate the data within them using PostgreSQL. Specifically to determine the number of individuals soon leaving into retirement at Pewlett Hackard. Initially in the early analysis we determined the number of individuals leaving per department however later was tasked with specically determining the unique individuals names and titles. Then providing a list of those who will begin a mentorship program to train oncoming employees.
  
### Results

  Using various conditionals in PostgreSQL using PGadmin4 I was able to aggregate the varying data and determine those titles who be retiring. Below are some examples resulting from the analysis:
  1. First I was tasked with retrieving all of the names and titles of those retiring soon, however I found that there were several duplicate employee numbers with differing title positions. It can be concluded by the from and to date that these employees had changed titles.
