# AWS Pricing, Billing, and Governance

[AWS Review Notes Table of Contents](https://github.com/pslucas0212/AWS-Review-Notes)

### Understanding AWS Pricing
There are 3 fundamental drivers of cost.
- Compute - Hourly from launch to termination
- Storage - The data you store in the cloud
- Outbund data transfer - Data in flight moving between systems

Free Offer Types
- 12 months free usage following your initial sign-up date to AWS
- Always free. Offers do not expire and are available to all AWS customers
- Trials - Short-term free trials starting from the date you activate a particular service

**EC2 Pricing** There are 5 ways to pay for Amazon EC2 instances.
- On demand - You pay by the hour or second without pre-pay
- Savings Plan - Commit compute usage measured by the hour on a 1 or 3 year term
- Reserved Instances - Commit payment on a 1 or 3 year term. Pay regardless of usage
- Spot Instances - Launch instance if spare capacity is available a particular price point
- Dedicated Host - Physical machine reserved just for you

**Lambda Pricing**
- Number requests including those invoked (test, etc.) from the AWS console
- Code Execution time from execution start in response to events to stop
- 1 million requests per month free

**S3 Pricing**
- Priced by storage class
- Storage number objects and size
- Data transferred out of S3 region
- Requests made for data and the amount of requests

**RDS Pricing**
- Running Clock hours
- Type of Database
- Storage
- Purchase type
- Database count
- API requests
- Deployment type
- Data Transfer

**Total Cost of Ownership (TCO)**
TCO is a financial estimate that helps you understand both the direct and indirect costs of AWS.

**Application Discovery Service** helps you plan migration projects to the AWS Cloud.
- Plan migration projects
- Used to estimate TCO
- Works with other servicesto migrate servers

Ways to reduce TCO in AWS
- Minimize capital Expenditures. AWS helps you minimize large capital expenditures, which reduces your TCO.
- Utilize Reserved Instances. AWS provides Reserved Instances to help you lock in savings and reduce your TCO.
- Right Size Your Resources. AWS helps you match the provisioning of resources to your usage needs to reduce your TCO.
- Use pricing calculator to maximize TCO


**WS Price List API**. The Price List API allows you to query the price of AWS services.
- Query using JSON or HTML
- Receive price alerts when prices change 

- **Studying for the Exam**
  - Pricing Calculator
    - Don't forget the Pricing Calculator helps you calculate the TCO.
  - TCO
    - Don't forget the ways a company can reduce their TCO.
  - Pricing
    - Don't forget how pricing is calculated for EC2, Lambda, S3, and RDS.
  - Price List API
    - Don't forget the Price List API is one way to determine the cost of services.
	
