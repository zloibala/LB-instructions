# LB-instructions


1. Created HW LB in us-east-1
2. Created 2 instances in us-east1 called "hw", and "hw2".
3. Created target group called "MyFirstTragetGroup", and added 2 instances "hw","hw2"
4. Created Auto Scaling Group --> Attach to exisiting LB --> Desired Capacity -1, Scaling: Min Desired Capacity -1, Max -2.
5. Created Dymanic Policy --> Policy Type --> Target Type, Metric Type --> Average CPU utilizaation. Target Value 80. 
6. Route 53 --> Create Record --> Name --> Enabled Alias --> Chosed Endpoint Alias to Application and classic LB --> region us-east1. 
