# AWS Resources Used in Cloud Networking




<details><summary>What is a VPC?</summary><p>

### Here's a short list of areas in your career where good whiteboarding skills are really helpful:

- Virtual Private Cloud
- Create a virtual networking environment
- Isolated section of your AWS services - keeps your stuff contained

It’s customisable:
- Private and public access (depending on what you’re architecting)
- IP ranges
- Security controls - NACL
- Connect to on premises infra via VPN/Direct connect - hybrid cloud
- Route Table
- Connect it to the internet or on premises infra
- NAT gateway - bastion/jumpbox
- VPC Peering (no transitive peering, you have to be explicit)

Your VPC sits inside a Region. Subnets sit inside a VPC.

NOTE: Your free AWS account comes with a default VPC and we’re going to create a custom VPC.

</p></details>





Pit Stop Topic

CICR Ranges:
/x is the size of the bytes - the smaller the number the more IP’s you can have
Octets - helps us determine our subnet IP ranges
Task:
http://cidr.xyz/


What is a Subnet? == AZ	
Can be private/public
Subset of your VPC
/16 is the largest for a subnet
/28 is the smallest for a subnet