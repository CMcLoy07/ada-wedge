# Applied Data Analytics: Wedge Project

Tools: Python v. 3.83; Jupyter Notebook; Google Big Query

File: wedge_project.ipynb

The ipynb file for this notebook contains all parts to complete each task. You will find the file has been broken up by sections that pertain the the respective task. 

### Task 1

For task one, the following items are done: 

a. unzips the large 15gb files
b. cleans the files by removing nulls, placing headers on all files, and changes delimiters to comma separated

### Task 2

For task one, the following items are done: 

a. connect to GBQ
b. write owner query in GBQ to utilize in Python
c. Use pythong to pull query and write to txt file for analysis

### Task 3

For task one, the following items are done: 

a. create a new database "Wedge_Task_3.db"
b. run 3 queries from GBQ
    1. sales by date, by hour
       -show the total spend in the store, number of transactions, and the number of items sold
    2. sales by owner by year by month
       - show the sales by owners by date
    3. sales by product description by year by month
       - shows the total spend by prodcut description
      -this query will be in a join that is required to utilize the department numbers from the wedge              document provided by Professor John Chandler
c. each of these queries will be placed into their own txt file and then uploaded the the new db of Wedge_Task_3.db


## Feedback

Looks good! You're done. A few notes as I was reading your code: 

* Your check of `filename.startswith("._")` is very specific. It might be better to test something like whether or not the file ends in CSV or ZIP or 
whatever you need.
* Strive for maximum file width of 80 characters. Some of your comments run over, which is fine, but just put them on the next line. This helps 
improve readability across platforms. 
* You still have comments like `# change this to your authentication information`. It's okay to delete comments I wrote!
* Good on you for writing the delete tables stuff. I often will set a flag like `clean_up = False` and then have a section that says `if clean_up :` which holds
the deletion code. That way I never accidentally run it when I'm running all the cells (thoughtlessly). 


