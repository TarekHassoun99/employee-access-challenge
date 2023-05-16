# Dataset Description

The data consists of real historical data collected from 2010 & 2011. Employees are manually allowed or denied access to resources over time. You must create an algorithm capable of learning from this historical data to predict approval/denial for an unseen set of employees.

## File Descriptions

- `train.csv`: The training set. Each row has the ACTION (ground truth), RESOURCE, and information about the employee's role at the time of approval.

- `test.csv`: The test set for which predictions should be made. Each row asks whether an employee having the listed characteristics should have access to the listed resource.
