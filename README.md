# AWS_ECS_Spring_Boot_Docker


~~~
1.	mvn clean install
2.	Start the docker container
3.	docker build -f Dockerfile -t aws-csr_spring-boot .
4.	docker images
5.	docker run -p 8080:8080 aws-csr_spring-boot

Run below commands for docker hub
-----------------------------------
docker tag aws-csr_spring-boot:latest mail4dhananjaya/aws-csr_spring-boot:latest
docker push mail4dhananjaya/aws-csr_spring-boot:latest



AWS CLI Commands
----------
1.  aws configure [set user name and password to aws cli]
2.	aws ecr get-login-password --region us-east-2 | docker login --username AWS --password-stdin 079371596533.dkr.ecr.us-east-2.amazonaws.com
3.	docker tag realspeed:latest 079371596533.dkr.ecr.us-east-2.amazonaws.com/realspeed:latest
4.	docker push 079371596533.dkr.ecr.us-east-2.amazonaws.com/realspeed:latest

~~~
