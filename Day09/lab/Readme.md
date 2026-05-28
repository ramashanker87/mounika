## Command to create cloudformation

    aws cloudformation create-stack \
    --stack-name moni-ec2-stack \
    --template-body file://moni-ec2-template.yaml \
    --capabilities CAPABILITY_NAMED_IAM \
    --profile devops

## Delete cloudformation command

    aws cloudformation delete-stack \
    --stack-name moni-ec2-stack \
    --profile devops