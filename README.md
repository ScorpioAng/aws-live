# Install flask on EC2 
# Either add "sudo" before all commands or use "sudo su" first

#!/bin/bash
yum update -y
yum install git -y
git clone https://github.com/ScorpioAng/aws-live.git
cd aws-live
pip3 install flask
pip3 install pymysql
pip3 install boto3
python3 EmpApp.py
