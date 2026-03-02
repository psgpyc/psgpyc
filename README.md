Hey 👋, I am [@psgpyc](https://github.com/psgpyc) (**Paritosh Ghimire**).  

I’m an data/analytics engineer from Nepal 🇳🇵.     

I am living in London, England 🏴󠁧󠁢󠁥󠁮󠁧󠁿 since 2023.  

I am currently pursuing Bsc.(Hons) Data Science at [The Open University](https://www.open.ac.uk/courses/statistics/degrees/bsc-data-science-r38/)  

I build data and analytics systems using [SQL](), [Python](), [dbt](), [Apache Airflow]() on [AWS]() & [Snowflake]() using [Terraform](). 

I am also learning [Apache Spark]().

- My Recent Projects:  

[Analytics Engineering, An Event-Driven Pipeline with dbt in Snowflake](https://github.com/psgpyc/WASH-Analytics-Engineering-Project)   

I built an event-driven ingestion and modelling pipeline for late-arriving data in S3. Events flow through SNS to SQS (with a DLQ), and Snowpipe auto-ingests the data into Snowflake RAW tables. From there, dbt standardises and validates the data, quarantines bad rows, builds integrated intermediate models, publishes dimensional marts for BI, and ships monitoring models for freshness and data quality.  


- I am currently working on:  

[Airflow on AWS ECS](https://github.com/psgpyc/Airflow-on-ECS-FARGATE)  
  
I set up Apache Airflow on [AWS ECS Fargate]() with Terraform — VPC networking, an Application Load Balancer for the web UI, Airflow services running in private subnets in Fargate containers, shared storage([EFS]()) access points for DAGs/logs, and secrets managed through AWS.  
Terraform state is managed in Amazon S3 using a remote S3 backend.  

Next, I’ll be authoring DAGs for my restaurant reservation pipeline and running them on this infrastructure.  



