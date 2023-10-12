# Basic Functions And Formulas

## Basic Functions and Formulas Sheet 1
This particular task explains the use of formulas and functions.
*Formulas* are user-defined expressions that combined values, cells references, operators and functions to produce a result. And they start with an equal sign (=).
*Functions* are pre-built formulas provided by excel to perform specfic operations, such as; *Sum, Average, If, Count, Date, Min, Max etc.*

### Excel Task 1
For this task, we were asked Determine the below using the provided Sales data.
1. the total sales revenue and profit generated.
2. the average revenue and units sold for every order.
3. Total Discount given in $.
4. Total number of sales recorded.
5. The highest profit generated.

For this Task, this involve the use of **SUM, COUNT, AVERAGE and MAX function**
For **no.1**, i used the **SUM** Function to get the Total sales Revenue and Profit Generated. The statement used is **=SUM(A2:A701)** For Total Sales Revenue 
And for Profit Generated the statement used is **=SUM(L2:L701)**.

For NO.2, i used the **AVERAGE**. For the average revenue the statement used is **=AVERAGE(A2:A701)**

For No.3,  i used the **SUM Function** to get the total discount given. the statment used is **=SUM(F2:F701)** 

For No.4, I used the **COUNT Function** to get the total number of sales recorded. The statement used is **COUNT(A2:A701)**.

For NO.5, Iused the **MAX Function** to get the highest profit generated. the statment used is **=MAX(L2:L701)**.


### Excel Task 2
For This task, we were asked to create a column named *Sales Range* return *High Sales* if the sales value is above average, otherwise, return *Low Sales.*

This task involve the use of the *IF function*. To carry out this task, i craeted a column and named it *Sales Range* and on the first cell, i inputted the *iF function statement* which is **(=IF(the logical test, Value_if_true, value_if_false)**. In this task, the logical test was if the sales value is above the average revenue, return true. 
The statement/function is as follows: **=IF(SalesValue>Average Revenue, "High Sales", "Low sales")**. This statement will return all sales vale above average as High sales and the ones below average as low sales.
