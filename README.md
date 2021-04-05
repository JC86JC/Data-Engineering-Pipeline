# Data-Engineering-Pipeline
A serverless data engineering pipeline on AWS.

The pipeline uses two lambda functions on AWS to load data from DynamoDB, and then carry out sentiment analysis on the corresponding wikipedia page. The results are then written into a S3 bucket, as shown in the diagram below



![image](https://user-images.githubusercontent.com/54278431/113527009-14af7280-958a-11eb-83db-082b01061e5d.png)


Results:

![image](https://user-images.githubusercontent.com/54278431/113527112-7bcd2700-958a-11eb-8365-0ac5b0f04c26.png)

![image](https://user-images.githubusercontent.com/54278431/113527141-9901f580-958a-11eb-8bf4-2a715b3cdad0.png)

