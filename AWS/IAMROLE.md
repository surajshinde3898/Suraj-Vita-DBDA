# IAM ROLE

1) It is known as identification Access Management role.for eg.if we want to go to college we want id to access the college.

2) It gives u the identity we can attach to any services to access.

3) Rules are used to authorize and it is attach to IAM i.e. what to allow and not to allow permissions.

4) In policies we attach rules and then policies are atach to IAM role.

  ex. If we want to connect EC2 service with s3 we have to create one IAM role for access in
  IAM we have to create policy which is written in json file i.e.it is to insert,delete access.
  then that policy is attached to IAM role and IAM role is attached with ec2 instance.
  
  

Command to Connect :--> `aws s3 ls`
