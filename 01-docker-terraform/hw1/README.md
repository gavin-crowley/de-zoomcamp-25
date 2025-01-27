# Module 1 Homework: Docker & SQL

## Question 1. Understanding docker first run 

What's the version of `pip` in the image?

Answer: **24.3.1**


## Question 2. Understanding Docker networking and docker-compose

Given the following `docker-compose.yaml`, what is the `hostname` and `port` that **pgadmin** should use to connect to the postgres database?

Answer: **db:5432**


## Question 3. Trip Segmentation Count

During the period of October 1st 2019 (inclusive) and November 1st 2019 (exclusive), how many trips, **respectively**, happened:
1. Up to 1 mile
Answer: **104,802**

2. In between 1 (exclusive) and 3 miles (inclusive),
Answer: **198,924**

3. In between 3 (exclusive) and 7 miles (inclusive),
Answer: **110,612**

4. In between 7 (exclusive) and 10 miles (inclusive),
Answer: **27,678**

5. Over 10 miles 
Answer: **35,202**


## Question 4. Longest trip for each day

Which was the pick up day with the longest trip distance?
Use the pick up time for your calculations.

Answer: **2019-10-31**


## Question 5. Three biggest pickup zones

Which were the top pickup locations with over 13,000 in
`total_amount` (across all trips) for 2019-10-18?
 
Answer: **East Harlem North, East Harlem South, Morningside Heights**


## Question 6. Largest tip

For the passengers picked up in October 2019 in the zone
named "East Harlem North" which was the drop off zone that had
the largest tip?

Answer: **JFK Airport**


## Question 7. Terraform Workflow

Which of the following sequences, **respectively**, describes the workflow for: 
1. Downloading the provider plugins and setting up backend,
2. Generating proposed changes and auto-executing the plan
3. Remove all resources managed by terraform`

Answer: **terraform init, terraform apply -auto-approve, terraform destroy**
