## 10 Weeks of CloudOps Challenge

### WEEK 2: Design a 3-Tier Architecture

#### Design Considerations: 

A 3-Tier Architecture consists of 3 independent modules: 
- <b>Data Tier (e.g., Databases: RDS, Aurora, MySQL, PostgreSQL, MongoDB):</b> Stores and retrieves, and manages data based on requests from the application tier, while ensuring data consistency and integrity.
- <b>Application Tier (e.g., Server: EC2):</b> Manages transactions, performs business logic and validation, processes client requests and responses in Presentation layer, and sends CRUD (Create, Read, Update, Delete) operations to Data Tier.
- <b>Presentation Tier (e.g., Client: IoT Devices):</b> Displays information to end users, handles user input and interactions, and sends process requests to Application Tier.

A well-structured, efficient, and secure 3-tier architecture includes the following:
- <b>High Availability (e.g., Route53, ELB, Multi-AZ Deployment):</b> Ensuring your application remains accessible and operational with minimal downtime. It involves redundant components and architectures designed to withstand failures and maintain service availability.
- <b>Scalability (e.g., EC2, ELB, NAT Gateway):</b> Ability of an application to handle increased workload by adding resources dynamically, ensuring the application remains responsive even during periods of high demand.
- <b>Fault Tolerance (e.g., Multi-AZ Deployment, ELB):</b> Designing systems to continue operating properly in the event of component failures. It focuses on redundancy, failover mechanisms, and automated recovery processes.
- <b>Custom VPC (e.g., Amazon VPC):</b> Creating a logically isolated section of the Cloud to launch a subset of resources in a virtual network with custom configurations (e.g., private vs public subnets).
- <b>Security (e.g., IAM, KMS, WAF):</b> Implementing measures to protect infrastructure, data, and applications from unauthorized access, data breaches, and other security threats.



#### IMPLEMENTATION

- TBD


---

#### RESOURCES 
- <b>Challenge Source:</b> https://github.com/piyushsachdeva/10weeksofcloudops
- <b>Cloud Platform:</b> [AWS](https://aws.amazon.com) 
- <b>IaC Tooling:</b> [Terraform](https://www.terraform.io)
- <b>CI/CD:</b> [Github Actions](https://docs.github.com/en/actions)

---

<p align='center'><a href='https://choosealicense.com/licenses/mit/' target='_blank'>MIT 
License</a></p>
