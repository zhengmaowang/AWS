# AWS lambda function 
The purpose of the lambda function is to monitor EC2 schedule change events, for example, EC2 instance retire events, the lambda code will get ec2 instance id information, then get EC2 tag information.
then call sns api to publish them.
