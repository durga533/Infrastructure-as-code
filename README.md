# Infrastructure-as-code

This template deploys a VPC, with a pair of public and private subnets spread across two Availability Zones. It deploys an internet gateway, with a default route on the public subnets. It deploys a pair of NAT gateways (one in each AZ), and default routes for them in the private subnets.
VPC CIDR ( If not given default CIDR of 10.192.0.0/16 will be taken ) 

Public subnet1 ( Default 10.192.10.0/24 ) 
Public subnet2  ( Default 10.192.11.0/24 ) 

Private Subnet1 ( Default 10.192.20.0/24 ) 
Private Subnet2  (Default 10.192.21.0/24 ) 

NAT gateway1

NAT gateway2 
