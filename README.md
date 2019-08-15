# python-analytics
Coding Customer churn prediction

File location:
https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Employee+Churn+in+Python/HR_comma_sep.csv

Exploratory data analysis and visualization of employee churn dataset using matplotlib and seaborn, model building and evaluation using python scikit-learn package.

Well, you got a classification rate of 97%, considered as good accuracy.

Precision: Precision is about being precise, i.e., how precise your model is. In other words, you can say, when a model makes a prediction, how often it is correct. In your prediction case, when your Gradient Boosting model predicted an employee is going to leave, that employee actually left 95% of the time.

Recall: If there is an employee who left present in the test set and your Gradient Boosting model can identify it 92% of the time.

Those employees who have the number of projects more than 5 were left the company.
The employee who had done 6 and 7 projects, left the company it seems to like that they were overloaded with work.
The employee with five-year experience is leaving more because of no promotions in last 5 years and more than 6 years experience are not leaving because of affection with the company.
Those who promotion in last 5 years they didn't leave, i.e., all those left they didn't get the promotion in the previous 5 years.
Data Analysis and Visualization Summary:
Following features are most influencing a person to leave the company:

Promotions: Employees are far more likely to quit their job if they haven't received a promotion in the last 5 years.
Time with Company: Here, The three-year mark looks like a time to be a crucial point in an employee's career. Most of them quit their job around the three-year mark. Another important point is 6-years point, where the employee is very unlikely to leave.
Number Of Projects: Employee engagement is another critical factor to influence the employee to leave the company. Employees with 3-5 projects are less likely to leave the company. The employee with less and more number of projects are likely to leave.
Salary: Most of the employees that quit among the mid or low salary groups.

Cluster done for happy or unhappy group with a medium one in between.
