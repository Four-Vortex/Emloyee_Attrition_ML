# Emloyee Attrition ML

**An organization's attrition rate is a statistic that measures the pace at which workers leave, either willingly or unwillingly. For HR teams to assess retention efforts and comprehend organizational dynamics, it is a crucial indicator of the rate of employee turnover, given as a percentage.**

This ML Project determines whether a emloyee will be retain by the organization or not based on some creteria.

## Process to Use the Model
1. Import the model (model.h5).
2. Create a DataFrame as follows:
   
     *{'number_project':[number_project],'average_montly_hours':[average_montly_hours],'time_spend_company':[time_spend_company]}*
   
       a. number_project - Number of project done by the emloyee
       b. average_monthly_hours - Hours spend by the emloyee daily on his/her working days.
       c. time_spend_comany - Number of years the emloyee is working on in the Organization.
4. Use the Dataframe and feed in the model to get the result.
