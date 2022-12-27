# Capstone_Project

## Usage:
```
# Install dependencies
npm install
# Start server
node server.js
```
## API details
- GET /
    - returns "Hello World"
- GET /load
    - query params:
        - scale -> time(ms) for which CPU will be blocked (default=random between 0ms to 10ms)
    - returns "OK" after execution

## Notes:
This is a POC prepared around the setup of kubernets cluster on cloud and managing applications on kubernets.
The POC has the following goals.
- Basic VPC setup for a kubernetes cluster on AWS
- EKS Cluster setup using eksctl
- Stateless and stateful workload on kubernetes
- Metrics system for kubernetes
- Autoscaling nodes and workload on kubernetes
