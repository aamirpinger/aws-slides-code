# Command to execute to create VPC:

```
aws cloudformation create-stack --stack-name basic-VPC --template-body file://cloud-formation-basic-vpc-yaml-file.yaml --parameters file://cloud-formation-basic-vpc-parameters.json --region=us-west-2
```
