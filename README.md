# inventory-manager-ci-cd-pipeline
Complete the CI/CD process with full integration an automation.

## Cronjobs
- A time based schedules
- It tell github actions to run your workflow at a regular interval

- * * * * * - 5 place holder values 
- First: minute (0 - 59)
- Second: hour  (0 - 23)
- Third: day of the month (1 - 31)  
- Fourth: Month (1 - 12)
- Fifth: Day of the week (0 - 6)
- *: Asterisk mean every

0 0 1 1 0
0 0 * * 1 - midnight everyday UTC
0 12 * * 1 - every monday at 12pm UTC
* * * * * - every minute
*/15 * * * * - every 15 minutes 
0 0 1,16 * * - 