# TRAINOCATE X AWS WORKSHOP

# SESSION 1: EC2 ESSENTIAL

## Amazon EC2 instance type

1. General purposes -
2. Compute optimized -
3. Memory Optimized - Ideal for high performance
4. Accelerated Computing - Use hardware accelerator to expedite data processing
5. Storage Optimized - Offers Low latency and high I/O operation per second (IOPS)

## Amazon EC2 Instance pricing option

1. On-demand
   - No upfront costs or minimum contracts.
   - Ideal for short-term irregular workloads.
2. Spot
   - Ideal for workloads with flexible start and end times
   - Offers savings over on-demand prices
   - Development or staging environment
   - You choose how much you pay for a cost.
   -
3. Reserved
   - Provides a billing discount over on demand pricing
   - Requires a 1-year or 3-year term commitment.
   - most indemand
4. Compute Saving Plan
   - Offers up to 66% saving over on-Demand cost for a consistent amount of compute usage
   - Require 1 year or 3 years term commitment
5. Dedicated Instance
   - An EC2 instance that runs in a VPC on hardware for a single customer
   - Higher cost
6. Dedicated Host
   - A pysical server
   - Same as Dedicated Instance

## Amazon EC2 Auto Scalling

- how the scale
- cost is the same
- problem in auto scalling is to customer or data will go in the data center provided
- proble, we dont have a single point of entry.
- to solve the proble we need a **Elastic LOAD BALANCER**

## Elastic Load Balancer

- Automatically distributes traffic across multiple resources
- Provide single point of contact in your Auto Scalling group

## How to deploy using EC2

- Setup server
  ECS > Instances > Pick a region > Launch instances > Pick OS >

- Setup network
  Network >

## Amazon Simple Notification Service

- Messages are published to topics
- Subscribe immediately receive message their topic

## Amazon Simpe Queue Services

- Send, store and receive messages between software components
- QUeue messages without requiring other services to be available.

## Serverless Computing

## AWS LAmbda

- Run code without provisioning or managing server
- Pay only for compute time wihle code is running
- Use the AWS services tto automatically trigger code.

For complex system, we dont do all in console. Usually we setup in code. Take the process and put it in cloud.

# SESSION 2: APPLIED GENAI
