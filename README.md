# hello--world
kpmg assesment
Challenge #1 A 3-tier environment is a common setup. Use a tool of your choosing/familiarity create these resources on a cloud environment (Azure/AWS/GCP). Please remember we will not be judged on the outcome but more focusing on the approach, style and reproducibility. 

https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/install-LAMP.html

Solution:

WEB TIER:

Step 1: Creating Your VPC and More
 

Step 2: Creating Your Web Tier Launch Template
Step 3: Create Auto Scaling Group
STEP 4: Create Application Tier Auto Scaling Group
STEP 5: Update Your Private Routing Table

DATABASE TIER:
         

Challenge #3 
We have a nested object. We would like a function where you pass in the object and a key and get back the value. The choice of language and implementation is up to you. Example Inputs object = {“a”:{“b”:{“c”:”d”}}} key = a/b/c object = {“x”:{“y”:{“z”:”a”}}} key = x/y/z value = a Hints: We would like to see some tests. 

A quick read to help you along the way - We would expect it in any other language apart from elixir. 

Solution:

Inputs 
object = {“a”:{“b”:{“c”:”d”}}} 
key = a/b/c 
object = {“x”:{“y”:{“z”:”a”}}} 
key = x/y/z value = a

Here, I’ll use object.get(key_name) to get the values of input keys.
Query the metadata of an ec2 instance within AWS and provide a json formatted output.
Retrieve the value of a particular data key.

1.Create an EC2 Linux instance on AWS
2.SSH into the instance
3.Install Python 3 and git on your instance
4.sudo yum install python3 git
5.Clone this repository
6.git clone https://github.com/bluprince13/aws-metadata-json
7.Install pipenv
8.sudo pip3 install pipenv
9.Open the repository on your instance
10.cd aws-metadata-json
11.Install project dependancies
12.pipenv install


=======================================================================================
HOW TO RUN 

1.Open the src folder
    cd aws-metadata-json/src
2.Run whichever script you need like:
    python3 get_metadata.py
    python3 get_key.py

