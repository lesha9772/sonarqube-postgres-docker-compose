# sonarqube-postgres-docker-compose
SonarQube with Postgres on docker-compose

Use the following docker-compose file and be up and running in minutes.

Start this stack with ``` docker-compose up ``` You can reach your SonarQube instance at http://localhost:9000 .
Use the default credentials admin/admin to login.


# Use sonarqube
You need to create a new project and generate a token. For example, you will see a command like 
```
 mvn sonar:sonar 
  -Dsonar.projectKey=test-app 
  -Dsonar.host.url=http://localhost:9000 
  -Dsonar.login=cea14c3edacfdc91d77ceca271e6dfc42a4d6548
```
