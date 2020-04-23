# aws_cloudformation
Udacity nano degree project, build high-availability web app using CloudFormation

All stack code is in cloudformation-stack.yml
The design chart is here:
https://www.lucidchart.com/invitations/accept/2ab3d7a0-65f3-43e6-9af7-b1a25430158c
Also in this image file:
Udacity Cloudformation Project.jpeg

To create the stack, run:
aws cloudformation create-stack --stack-name udacity-web-app --template-body file://./cloudformation-stack.yml  --region=us-west-2 --capabilities CAPABILITY_IAM

To update the stack, run:
aws cloudformation update-stack --stack-name udacity-web-app --template-body file://./cloudformation-stack.yml  --region=us-west-2 --capabilities CAPABILITY_IAM