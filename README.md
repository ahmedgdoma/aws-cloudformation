# aws-cloudformation
to ```create``` the task run the command:

```aws cloudformation create-stack 
--stack-name cloudFormationProject 
--template-body file://project.yml  
--parameters file://project-parameters.json 
--capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" 
--region=us-east-1
```

the current load balancer public url is: http://cloud-webap-p2gltzyi4xi7-1828055571.us-east-1.elb.amazonaws.com/ 
