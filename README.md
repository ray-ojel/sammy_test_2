# sammy_test_2
Due 10/5/2020 by 11:59 PM


### Before Step 1: 
Install Anaconda https://www.anaconda.com/products/individual and make sure to "ADD TO PATH" when installing.


### In Windows CMD:

1. Change to the ray_assignments directory.

2. Activate anaconda using 

`$ C:/Users/[USERFOLDER]/anaconda3/Scripts/activate`

3. Create a new anaconda environment

`(base)$ conda create -n [ENVIRONMENT NAME] python=3.6`

4. Activate the new environment

`(base)$ conda activate [ENVIRONMENT NAME]`

5. In that environment, install pyodbc, pandas, and numpy using pip


### In Git Bash: 

1. Change to Documents/ray_assingments/ folder.

2. Clone this repository to that directory

1. Create a new file called test2.py

2. vim into the file and insert the code that answers the following: 

```
George comes and asks you to create a cash flow model. He says that you need the following table:

YodleeTransactions: Account_Name, PostDate, CashAmount, CategoryType, Location.

He says he wants to know how much cash each account spent in each category.

```
3. Git status, add, commit, and push.


### Hints:
* Use sql in python. 

* You need to use pyodbc to connect to 'LQDC' database, using a fake (whatever you want) server, username and password variables.

* In sql, you need to select the account name, sum of cash, and the category from the table grouped by CategoryType and Account_Name.

* Essentially, the results table need to have the following columns: 

`Account_Name, SumAmount, CategoryType`

* You need to convert sql to dataframe. 

* You need to print the dataframe as a result. Using `print(dataframe)` at the end of ur code.
