# aws_cloudformation
Udacity nano degree project, build high-availability web app using CloudFormation<br/>

All stack code is in cloudformation-stack.yml

The design chart is here:<br/>

https://www.lucidchart.com/invitations/accept/2ab3d7a0-65f3-43e6-9af7-b1a25430158c

Also in this image file:<br/>

Udacity Cloudformation Project.jpeg

To create the stack, run:<br/>

aws cloudformation create-stack --stack-name udacity-web-app --template-body file://./cloudformation-stack.yml  --region=us-west-2 --capabilities CAPABILITY_IAM

To update the stack, run:<br/>

aws cloudformation update-stack --stack-name udacity-web-app --template-body file://./cloudformation-stack.yml  --region=us-west-2 --capabilities CAPABILITY_IAM