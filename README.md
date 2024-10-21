# AWS projects
# Developing a 3 tier web application with Amazon EC2 and Amazon Aurora

This project is a step by step process involving connecting an interactive website to AWS Aurora database
Images have been placed in the AWS Project folder.

Based on the well architected framework ; i ensured that the following were followed

For Reliability, I created snapshots of my RDS database to safeguard against data loss and ensure quick recovery. Additionally, I implemented Multi-AZ deployments for Amazon Aurora, which not only enhances availability but also provides automatic failover capabilities—keeping our application resilient even in the face of unexpected challenges.

When it comes to Performance Efficiency, I optimised instance types based on workload requirements and leveraged Auto Scaling to handle varying traffic loads seamlessly. 

For Security, I enforced strict IAM policies and used VPCs with security groups to control access meticulously.

Lastly, in terms of Cost Optimization, I regularly reviewed usage patterns and rightsized instances accordingly, ensuring i am getting the best value without compromising performance. In terms of compute power a opted for burstable classes instead of the predefined selected memory optimized which had a high cost than the former

I’m grateful for the opportunity to apply these principles in a real-world scenario and look forward to further enhancing our architecture based on these foundational pillars.




 
