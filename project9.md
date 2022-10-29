##Continuous integration pipeline for tooling website
#install jenkins
`sudo apt update`
`sudo apt install default-jdk-headless`
`wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -`
`sudo sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > \
    /etc/apt/sources.list.d/jenkins.list'`
`sudo apt update`
`sudo apt-get install jenkins`

#confirm jenkins status
`sudo systemctl status jenkins`
![alt text](./image/jenkins.PNG)

`sudo cat /var/lib/jenkins/secrets/initialAdminPassword`
`cat /mnt/apps/README.md`
![alt text](./images/login.PNG)
