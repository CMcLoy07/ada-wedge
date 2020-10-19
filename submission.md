
# Applied Data Analytics

## Wedge Project

<!-- Any general commentary you'd like to say about the project --> 

The project was fun and extremely hard. It was very challenging at times, however, I took longer than most due to really combing through the code to make sure that I understood what each step was doing. At times, it was very stressful to keep up with the workload this required, but in the end proved to be a fun project. 

### Task 1

### Task 2

### Task 3

* Files for this task: 
<!--  List of file or files here  --> 

wedge_project.ipynb

For this file within my repo, it compiles task 1, 2, and 3 all together. For task one, it takes zip files, unzips them, cleans them up to remove null values, add headers, and split on proper delimiters. Once this is done, it uploads the _clean.csv files into Google Big Query as tables. 

For task 2, this file it will connect to the GBQ instance and build a list of owners, take a sample of the owners and extract all the records associated with those owners and write them to a txt file.

For Task 3, we will create a new database, run three different queries from GBQ, write them to txt files, and upload them to the new database

## Query Comparison Results

Fill in the following table with the results from the 
queries contained in `gbq_assessment_query.sql`. You only
need to fill in relative difference on the rows where it applies. 
When calculating relative difference, use the formula 
` (your_results - my_results)/my_results)`. 



|  Query  |  Your Results  |  My Results | Difference | Rel. Diff | 
|---|---|---|---|---|
| Total Rows  |  85760139 | 85760139   |  0 |  0 |
| January 2012 Rows  | 1070907  | 1070901  |  0 | 0  |
| October 2012 Rows  | 1042287  | 1042287  | 0  | 0  |
| Month with Fewest  | Feb  |   | Yes | NA  |
| Num Rows in Month with Fewest  | 6556770  |  6556700 | 0  | 0  |
| Month with Most  | May  |   | Yes | NA  |
| Num Rows in Month with Most  | 7578372  |7578372   | 0   | 0  |
| Null_TS  | 7123792  | 7123792  | 0  | 0  |
| Null_DT  | 0  |  0 | 0  | 0  |
| Null_Local  | 234843  | 234843  | 0  | 0  |
| Null_CN  | 0  | 0  |  0 | 0  |
| Num 5 on High Volume Cards  |14987.0   | 14987  | Yes | NA  |
|  Num Rows for Number 5 | 460630  | 460630  | 0  | 0  |
| Num Rows for 18736  |12153   | 12153  | 0  | 0  |
| Product with Most Rows  | banana organic  | banana organic   | Yes  | NA  |
| Num Rows for that Product  | 908639  | 908369  |  0 | 0  |
| Product with Fourth-Most Rows  | avocado hass organic  | avocado hass organic  | Yes  | NA  |
| Num Rows for that Product  | 456771  | 456771  |  0 | 0  |
| Num Single Record Products  | 2769  | 2769  | 0  | 0  |
| Year with Highest Portion of Owner Rows  |2014   | 2014 | Yes  | NA |
| Fraction of Rows from Owners in that Year  |.7591   | .7591  | 0  |  0 |
| Year with Lowest Portion of Owner Rows  |2011   | 2011  | Yes  | NA |
| Fraction of Rows from Owners in that Year  |.7372   | .7372 | 0  | 0  |

## Reflections

<!-- I'd love to get 100-200 words on your experience doing the Wedge Project --> 
The wedge project was overall really intersting and fun. It challenged me on a great deal of things. Coming into this project with little to no Python, I found myself hating life a great deal but still enjoying the work. If I can give one piece of advice, it would be for the MSBA counslers to stress python prior to entering the program for at least 3 months to allow for a better grasp with this project. 