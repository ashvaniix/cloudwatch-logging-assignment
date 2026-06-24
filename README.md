# Set Up Centralized Logging with CloudWatch

## Objective
Configure CloudWatch to collect and monitor logs from EC2 instances and create dashboards for monitoring.

## Planned Steps

### 1. Launch EC2 Instance
- Create an EC2 instance.
- Configure security groups.

### 2. Create IAM Role
- Attach CloudWatchAgentServerPolicy.
- Assign role to EC2 instance.

### 3. Install CloudWatch Agent
- Install CloudWatch Agent on EC2.

### 4. Configure Logging
- Configure agent to collect system and application logs.

### 5. Send Logs to CloudWatch
- Create log groups and log streams.

### 6. Create Custom Metrics
- Configure metrics for CPU, Memory, Disk and Network.

### 7. Create Dashboard
- Create a CloudWatch dashboard.
- Add widgets for monitoring.

## Expected Deliverables

- CloudWatch Logs configured for EC2.
- Centralized logging enabled.
- Custom CloudWatch Dashboard.

## Challenges Faced

AWS account activation was pending because billing/payment verification was required. Therefore, practical implementation could not be completed. The task was studied and documented theoretically.

## Conclusion

The CloudWatch centralized logging process was understood and documented. Practical implementation will be completed once AWS account access becomes available.
