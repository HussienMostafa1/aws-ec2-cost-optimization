# aws-ec2-cost-optimization
# AWS EC2 Cost Optimization

## Problem

The development EC2 instance was running continuously, resulting in unnecessary compute costs during non-working hours.

## Solution

Implemented an automated scheduling solution using AWS Lambda to start and stop the EC2 instance based on operational requirements.

This automation reduced unnecessary resource consumption and eliminated manual intervention.

## Architecture

EC2 Instance ← AWS Lambda ← Scheduled Trigger

## Results

| Metric           | Before  | After   |
| ---------------- | ------- | ------- |
| Monthly EC2 Cost | $343.83 | $169.56 |

### Savings

* Monthly Savings: $174.27
* Cost Reduction: 50.69%

## Screenshots

### Before Optimization

![Before](screenshots/before-cost.png)

### After Optimization

![After](screenshots/after-cost.png)

### AWS Lambda Automation

![Lambda](screenshots/lambda-function.png)

## Technologies Used

* AWS EC2
* AWS Lambda
* Python
* boto3

## Benefits

* Reduced infrastructure costs
* Automated resource management
* Improved cloud cost efficiency
* Reduced manual operational tasks
