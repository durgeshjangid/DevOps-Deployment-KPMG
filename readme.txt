This is the 3 tier application infra. 3 tier is a clinet server architecthre in which 3 layers present.  
1. GUI or presentation layer
2. Logic layer, where the logic process like server/ec2 instance
3. Date layer, where the data will store and access. 

here i set up infra for 3 tier application in AWS pubic cloud. I used cloud formation to create the infra in AWS. 

=======================================================================================================================

-> VPC  :Done 
-> DNS for VPC : Done
-> Route table - to redirect the traffic, attached to VPCs : Done
-> Subnets  : Done
	  Public 
	  Private 
  	DB subnet 
-> IGW - To make subnet public and allow outside internet user to access LB : Done
-> LB - to balance & distribute  the traffic load : Done
-> LB  SG - to control the access to load balancer.  : Done
-> ASG- for scale out and scale in EC2. : Done
-> EC2  - for process the logic : Done
-> DB -  for store and access data : Done
-> SG - to control the access to DB : Done
