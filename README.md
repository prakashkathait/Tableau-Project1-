# HR-Dashboard

### Dashboard Link : https://public.tableau.com/views/HRDB_17190525498290/HRDB?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link

## Problem Statement

This dashboard helps to identify employees details of company named "Awesome Chocolates" and gives the view of employees in various factors like - 
1. Total jobs available in the market.
2. Gender Distribution
3. Age wise spread of staff's.
4. Top 3 most paying employees in different departments.
5. Head count trends over the time.
6. Qualifications vs salary 
7. Employee's leave balances.


- Creating Calculated field for checking employee leave balance greater than 20

       
        Staff more than 20 days leave= 
        
        IF[Leave Balance]>20 THEN 1 ELSE 0 END
        
Snap of new Measure in tableau ,

![Measure addition](https://github.com/prakashkathait/Tableau-Project1-/assets/166843819/7600db46-484d-40af-a021-aac126c9d87d)
)

# Snapshot of Dashboard (Tableau)

![DB Snap](https://github.com/prakashkathait/Tableau-Project1-/assets/166843819/2edb8d27-eedb-496a-90d1-93084447d87d)




# Insights

A single page report was created on Tableau & it was then published to Tableau public server.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Employess = 161
   
   Number of Male Employees = 73

   Number of Female Employees = 88
           
### [2] Top Earners 
Employee Ids- 

AC0121

AC0052

AC0073

  
 ### [3] Majority of staffs are 30 to 40 years old.

 Female - 51.76%

 Male - 48.24%

 ### [4] Over the time Company strength increases 
        
 Highest nos. of male and female joined in the FY-2023
 
 Female - 88
 
 Male - 73
 
 ### [5] Master's degree Holders are get paid more
 
  ### [6] Sales & Marketing People have high leave balances.
