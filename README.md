## Store-Sales_analsis using Excel
### **Project Target**:
Create an annual sales report to understand customers and grow more sales
### **Requirements**
1. Validate and clean data
2. Manipulate data and get insights
3. Design a dashboard

### Data Validation and Cleaning
- Check nulls using filtering:
  =ISBLANK()"
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
  |---|---|
  |44|Adult|
  |29|Teenager|
  |62|Senior|
  |18|Adult|

~~~
=IF(E2>=50,"Senior",IF(E2>=30,"Adult","Teenager"))
~~~

- add month column
  tables:
  |Date|Month|
  |---|---|
  |12/4/2022|December|
  |11/4/2022|November|
  |3/4/2022|March|
  |2/5/2022|February|

  ~~~
  =text(G2,"mmmmmm")
  ~~~

  ## Dashbord

[File Link] (https://1drv.ms/x/s!Ap2nH5tsRfqBi2PXbn9FT2FlHqxs)

!(![Screenshot (11)](https://github.com/mariem888/Store-Sales_analsis/assets/82527663/a5156aa6-f518-4d5c-ad27-7bc2daa2daae))

## Insights
1. which month got the highest sales and orders?
   
![Screenshot (13)](https://github.com/mariem888/Store-Sales_analsis/assets/82527663/b68acb93-5f20-4886-93a9-95ccaed5aeea)

3. who purchased more men or women?
   
![Screenshot (14)](https://github.com/mariem888/Store-Sales_analsis/assets/82527663/df4adf64-b96b-4c3f-b320-6f16de5e3991)

4. what are the different orders status?
   
![Screenshot (17)](https://github.com/mariem888/Store-Sales_analsis/assets/82527663/d2bfc939-8bfa-4c96-8f70-261fc738ae43)

5. list top 10 states contributing to the sales?

![Screenshot (15)](https://github.com/mariem888/Store-Sales_analsis/assets/82527663/3abc70f6-e016-4f3d-8438-aaf76fad0649)

6. relation between age and gender
   
![Screenshot (16)](https://github.com/mariem888/Store-Sales_analsis/assets/82527663/96819c14-9bd7-4e72-8628-02aff14aac49)

7. which channel is contributing to max sales?

![Screenshot (18)](https://github.com/mariem888/Store-Sales_analsis/assets/82527663/72365b7c-2a9f-44d1-973c-f84f6d5e1679)








