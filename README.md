# CloudFormation VPC Example

1. Contains a cloudformation template called "Fincity-Example-VPN.json" that can be used to quickly deploy the VPC on AWS.

2. Contians architecture diagram that explains the VPC connections of the VPC. 
    - The VPC contians 4 subnets across 2 regions (2private subnets / 2 public subnets). 
    - Public subnets can reach internet via the IGW and private subnets can reach the internet via NAT gateway.
    
Note: Virtual Private gateway / VPN connection / VPN Customer gateway / VPC Peering : These 4(shown in the diagram) will not be created by the Cloudformation template as they require secondary endpoints.
