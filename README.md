# Cost saving on AWS

Tips and tricks to save cost and optimize on AWS.

## General

* Managed services > others
  * Aurora > RDS
* Serverless > servers
* Scheduling development/staging/testing environments
  * Take advantage of IAC

## EC2

### EC2 Spot Instances

* Up to 90 % off on-demand
* Same infrastructure as on-demand
* Catch
  * Interruptions happen when OD needs capacity (no bidding)
* Best for
  * Stateless
  * Flexible
  * Fault-tolerant workloads?
* Main objective
  * Choose different instance types, sizes and AZs in a single fleet

### S3

* Intelligent tiering

## References

* [Accelerate Growth and Save Up to 90% on Compute Costs - (Webinar 1 of 3)](https://www.youtube.com/watch?v=fOsiCJX_2Ds)

## Glossary

* IAC = infrastructure as code
* S3  = simple storage service
* EC2 = elastic compute cloud
