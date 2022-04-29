# aws-cloudformation
to ```create``` the task run the command:

```aws cloudformation create-stack 
--stack-name cloudFormationProject 
--template-body file://project.yml  
--parameters file://project-parameters.json 
--capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" 
--region=us-east-1
```

