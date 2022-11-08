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
	
### Understanding Billing Services
There are several tools available to help you track your ongoing spend.

**Budgets**. Budgets allows you to set custom budgets that alert you when your costs or usage exceed your budgeted amount.
- Improve planning and cost control
- Cost, usage, and reservation budgets
- Budget alerts

Budget Types
- Cost Budgets.  Plan how much you want to spend on a service
- Usage Budgets.  Plan how much you want to use a service
- Reservation Budgets. Set Reserved Instances or Savings Plan utilization or coverage targets

You can monitor Free Tier usage to ensure you don't accidentally exceed Free Tier limits and incur unwanted costs. You can set up an alert notification for when your account is approaching a particular dollar amount.

**Cost and Usage Report** The Cost and Usage Report contains the most comprehensive set of cost and usage data.
- Aggregate usage data on a daily, hourly, or monthly leve
- The Cost and Usage Report gives you the ability to do a deep dive into your AWS cost and usage data. Once set up, you can download the report using the Amazon S3 console.

**Cost Explorer** Cost Explorer allows you to visualize and forecast your costs and usage over time.
- Visualize costs over time
- View past 12 months
- Forecast for up to 3 months
- If you are considering your options for Savings Plans, AWS Cost Explorer can analyze your EC2 usage over the past 7, 30, or 60 days.

**Cost Allocation Tags** Tags are useful for tracking spend.
- Tags allow you to label resources using a key and value pair.
- Tags allow you to track costs via the cost allocation report. 

- **Studying for the Exam**
  - Budgets
    - Going into the exam, don't forget you can be alerted when your usage exceeds a defined threshold using Budgets.
  - Cost and Usage Report
    - Remember that the Cost and Usage Report provides the most detailed set of AWS cost and usage data available.
  - Cost Explorer
    - Don't forget Cost Explorer helps you visualize and forecast spending.
  - Cost Allocation Tags
    - Don't forget that tags can help you track spend.

**Exploring Governance Services** Governance and management services help you maintain control over cost, compliance, and security across your AWS accounts.

**Organizations** Organizations allows you to centrally manage multiple AWS accounts under one umbrella.
- Group multiple accounts
- Automate account creation
- Single payment for all accounts
- Allocate resources and apply policies across accounts

Master Payer/Root Organization -> Organizational Units -> Member accounts.  Service control Policies SCP - enforce permissions that you want everyone in the organziation to use.

Organization Benefits
- Consolidated Billing. The advantage of consolidated billing is that you receive one bill for multiple accounts.
- Cost Savings. You'll receive volume discounts since usage is combined across accounts. 
- Account Governance. You have a quick and automated way to create accounts or invite existing accounts. 
- Organizations allows you to save money using Reserved Instance (RI) sharing. RI sharing allows all accounts in the organization to receive the hourly cost-benefit of RIs purchased by any other account. You can always turn off RI sharing using the master payer (or root) organization.

**Control Tower**. Control Tower helps you ensure your accounts conform to company-wide policies.
- Helps set up new accounts using a multi-account strategy
- Works directly with AWS Organizations
- Enforces the best use of services across accounts
- Provides a dashboard to manage accounts
- Control Tower allows you to govern your multi-account environment by enabling cross-account security audits or preventing or detecting security issues through mandatory or optional guardrails.

**Systems Manager**  Systems Manager gives you visibility and control over your AWS resources.
- Automate operational tasks on your resources
- Group resources and take action
- Patch and run commands on multiple EC2 instances or manage RDS instances
- Systems Manager allows you to auto-patch software running on EC2 instances according to a schedule.

**Trusted Advisor** Trusted Advisor provides real-time guidance to help you provision your resources following AWS best practices.
- Helps you understand best practices
- Trusted Advisor helps reduce your overall costs by monitoring service limits.

**License Manager** License Manager helps you manage software licenses.
- License Manager. Manage on-premises and AWS licenses
- Track licenses for Oracle, Microsoft, SAP, and more

**Certificate Manager**. Certificate Manager helps you provision and manage SSL/TLS certficates.
- Povides public and private certificates for free
- Integrates with Elastic Load Balancing, API Gateway, and more

- **Studying for the Exam**
  - Organizations
    - Don't forget Organizations saves you money through consolidated billing. Also, remember the importance of SCPs.
  - Control Tower
    - Don't forget Control Tower helps you enforce best use of services across your organization.
  - Systems Manager 
    - Remember that Systems Manager helps you maintain your resources through automatic patching and updates.
  - Trusted Advisor
    - Remember the recommendations made by Trusted Advisor.
  - License Manager
    - Remember that License Manager helps you manage on-premises or AWS-based Oracle licenses.
  - Certificate Manager
    - Remember that Certificate Manager provides free public certificates.










