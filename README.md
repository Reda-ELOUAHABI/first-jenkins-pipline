#Jenkins

##install jenking 
##run localhost:8080
##log in [reda reda , or find your admin passwors in apdata ,,, they will give you]
##to link jenkins with dockerHub , add your  credentials in manage credentials (username+password) and call it a name in the ID , you will use the ID in the Jenkinsfile to setup your pipline github=>jenkins=>dockerHub
##create a new job of pipline type , describe it , the add this  poll SCM in build triggers : * * * * *
wich means every minute
##add your pipline of type : pipline script from SCM [source code management] , then choose git , then add your repo url (the http one in my case + ma ke it public also)


<!-- another short one  -->
https://youtu.be/ac9PMyB268s?t=150
https://devops4solutions.com/publish-docker-image-to-dockerhub-using-jenkins-pipeline/