Terraform file for creating a webserver with a simple text 
used AWS CLI - AWS Configuration - Local for AWS credentials
Created new VPC.
Created a subnet.
Created custom route table.
Subnet association with the route table.
Created security group to allow port https (443) http (80) SSH (22).
Created a network interface (NIC) with an IP in the subnet which was created earlier.
Assign a Elastic IP to the network interface. 
Create a ubuntu instance with some user data to spin up a apache server.
This was a great experince running this on jenkins
