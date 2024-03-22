Create an EC2 Instance,
Create a Snapshot for the volume of created EC2,
Create a Lambda Function with Python as a run time,
Copy the script and past it in the code editor of lambda function created,
Test it by manually,
If face issues with Describing Snapshots and Instances, Add those policies for this Lambda-function role which can be found in the configuration tab of Lambda Function,
Test it again by deleting the Instances created,
Snapshot will remain stored so test it again to delete it.
We can integerate with CloudWatch.