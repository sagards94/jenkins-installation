# jenkins-installation

## Linux Server
`###### sudo wget -O /etc/yum.repos.d/jenkins.repo \https://pkg.jenkins.io/redhat/jenkins.repo
###### sudo rpm --import https://pkg.jenkins.io/redhat/jenkins.io.key
##### sudo yum upgrade
##### sudo yum install jenkins
##### sudo yum install java
##### sudo apt install git make gcc 
##### sudo systemctl enable jenkins
##### sudo systemctl start jenkins
##### sudo systemctl status jenkins`


## Ubuntu Server
###### `sudo apt-get update
#####  sudo yum install java
#####  wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -
##### sudo sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
##### sudo apt-get update
##### sudo apt-get install jenkins
##### sudo apt install git make gcc 
`
