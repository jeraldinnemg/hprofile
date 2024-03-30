# Building my DevOps Portfolio 🚀

## Project 9: Github Actions for CICD.
One of the benefits of working at EY is Udemy for Business. I enrolled in the DevOps Projects | 20 Real-Time DevOps Projects course to enhance my DevOps portfolio and I’m sharing this process for educational purposes.


### Marketplace Actions used: 
🖤Checkout
🖤Sonar scanner
🖤Sonar Qualitygate
🖤AWS ECR
🖤AWS ECS Deploy task definition

### Steps
Github Setup 
⏭️Fork git repo
⏭️SSH Login
⏭️Integrate with VSCode

Test code
⏭️Workflow & Job
⏭️Maven & Checkstyle
⏭️Sonar scanner
⏭️Sonar cloud

Build & Upload Image
⏭️Job in workflow
⏭️Build Docker image
⏭️Upload AWS ECR

Deploy to ECS
⏭️Job in workflow
⏭️Deploy ECS Task definition
⏭️RDS for app container


## Github action CICD implementation
- Diagram
![Diagram](images/githubActions-CICD.drawio.png)
- CICD Github actions
![cicd](images/cicd-githubactions.png)
- Testing job
![Testing job](images/qualitygate-passed.png)
- Sonar cloud
![sonarcloud](images/sonarcloud.png)
- Rule quality gate
![Quality gate](images/qualitygaterule.png)
- Testing quality gate failed with the rule set
![Testing Quality gate failed](images/qg-failed.png)
- AWS ECR
![ECR](images/ecr-image.png)
- AWS ECS Service
![AWS ECS Service](images/ecs-service.png)
- Load Balancer
![Load Balancer](images/load-balancer.png)
- Target group healthy
![tg](images/target-group-healthy.png)
- Marketplace Githubactions used
![checkout](images/actions-checkout.png)
- Marketplace Githubactions used
![sonar-scanner](images/actions-sonnar-scanner.png)
- Marketplace Githubactions used
![sonar-qg](images/actions-sonar-qualitygate.png)
- Marketplace Githubactions used
![ecr](images/actions-aws-ecr.png)
- Marketplace Githubactions used
![ecs](images/actions-aws-ecs.png)

# Prerequisites
#####
- JDK 11
- Maven 3
- MySQL 8 

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
# Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql
#testing
