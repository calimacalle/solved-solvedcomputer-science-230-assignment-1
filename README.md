Download Link: https://assignmentchef.com/product/solved-solvedcomputer-science-230-assignment-1
<br>
Learning objectives: Review arrays.

Assignment:

A survey of the households in a town is being scrutinized for familiesbelow the poverty level. Each recordcontains data for one household, including a four-digit identification number,the annual income for the household, and the number of household members.Create a class, Household, that contains an ID number(an int), an income (a double), and a numberof household members (an int). Enter the data via the constructor. You willneed a getter for each field, but no setters are needed for this program.

Create a class, HouseholdStatistics, with a main() method. Read from standard input the name of a textfile, then read the survey results from the file until all have been read. Assume that each line of the file containsone ID number, one income, and one number of household members. As you read the data create a Household object and putthe data into it. Then put the object into an array or ArrayList of Household objects. Assume that no more than 25 households weresurveyed. Print a three-column table displaying the data as shown below. Calculate and display the average householdincome and display a list of the identification numbers of the households thatexceed the average, separated by commas.

Determine the percentage of households with incomes below the povertylevel. Compute the poverty level incomeusing the formula, p = $6500.00 + $750 * (m-2), where m is thenumber of members of the household. Thus the poverty level increases as m getslarger. (Warning: as given this formula may introduce a program bug.) List the identification numbers of thehouseholds that are below the poverty level, separated by commas.

Example:

Identification Number Annual Income Household members

1041 $12180.00 4

1062 $13240.00 3

1327 $19800.00 2

1483 $22458.00 8

1900 $17000.00 2

2112 $18125.00 7

2345 $15623.00 2

3210 $3200.00 6

3600 $6500.00 5

3601 $11970.00 2

4725 $8900.00 3

6217 $10000.00 2

9280 $6200.00 1

Average income = $12701.23

Households above the average income:

1062, 1327, 1483, 1900, 2112, 2345

Households below the poverty level:

3210, 3600, 9280