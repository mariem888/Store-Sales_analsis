### Store-Sales_analsis using Excel
## **Project Target**:
Create an annual sales report to understand customers and grow more sales
**Requirements**
1. Validate and clean data
2. Manipulate data and get insights
3. Design a dashboard

### Data Validation and Cleaning
- Check nulls using filtering:
  '''
  =ISBLANK()
  '''
// To know the Number of blanks in a column
- Remove Duplicates
// have 5 duplicates 
- Check Consistency:
// Gender's values are Female, Male, F, M
// by Find and replace: find F and repalce it with Female and find M replaced it with Male

### Data Manipulation
- Add Age group column
  tables:
  |Age|Age Group|
  |44|Adult|
  |29|Teenager|
  |62|Senior|
  |18|Adult|

''' 
=IF(E2>=50,"Senior",IF(E2>=30,"Adult","Teenager"))
'''

- add month column
  tables:
  |Date|Month|
  |12/4/2022|December|
  |11/4/2022|November|
  |3/4/2022|March|
  |2/5/2022|February|

  '''
  =text(G2,"mmmmmm")
  '''





