# jenkins-casc
Jenkins configuration as code

Reference:
https://www.digitalocean.com/community/tutorials/how-to-automate-jenkins-setup-with-docker-and-jenkins-configuration-as-code


#### docker build command
```
docker build -t jenkins:casc .
```

#### docker run command
```
docker run --name jenkins --rm -p 8080:8080 --env JENKINS_ADMIN_ID=<USERID> --env JENKINS_ADMIN_PASSWORD=<PASSWORD> jenkins:casc
```
