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




DOCKER :
Jenkins Password Admin path: 
C:\ProgramData\Jenkins\.jenkins\secrets\initialAdminPassword

# commands
# docker build .  or best build -t imageName . [imageName] [Path]
# docker run -it f10f459c3e7d[imageId] or best docker run [imageName]

//wsl home Location[in the network]: \\wsl$\Ubuntu\home

# open closed tab chrome: clt shift T
# start . == to open project explorer || Win + E || wsl : explorer.exe .
# start cmd.exe or start wsl.exe to open wsl/cmc
# wsl -l -v || wsl --list
# wsl --set-default-version 2
# wsl --set-version Ubuntu-20.04 2
# linux Version: cat /etc/*-release
# windows version: win+R tap winver




# To run a command as administrator (user "root"), use "sudo <command>".
# See "man sudo_root" for details.

# Welcome to Ubuntu 20.04.3 LTS (GNU/Linux 5.10.16.3-microsoft-standard-WSL2 x86_64)

#  * Documentation:  https://help.ubuntu.com
#  * Management:     https://landscape.canonical.com
#  * Support:        https://ubuntu.com/advantage

#   System information as of Sun Nov 28 12:34:10 +01 2021

#   System load:  0.16               Processes:             8
#   Usage of /:   0.5% of 250.98GB   Users logged in:       0
#   Memory usage: 8%                 IPv4 address for eth0: 172.18.136.241
#   Swap usage:   0%

# 1 update can be applied immediately.
# To see these additional updates run: apt list --upgradable


# The list of available updates is more than a week old.
# To check for new updates run: sudo apt update


# This message is shown once a day. To disable it please create the
# /home/reda/.hushlogin file.




<!-- run an image : docker run --rm -d  -p 8000:8000/tcp node-pip:latest -->

<!-- push an image directly: docker push redaelouahabi98/node-pip:latest -->