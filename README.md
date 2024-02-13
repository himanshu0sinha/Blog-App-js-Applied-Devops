# explore-India-js-Applied-Devops

Applied DevOps Project

tools used:
Github
Docker
AWS EC2
Jenkins

steps:

1.launched ec2 instance (applied-devops)
    2sudo apt update
    3  sudo apt install openjdk-11-jre
    4  java -version
    5  curl -fsSL https://pkg.jenkins.io/debian/jenkins.io.key | sudo tee \   /usr/share/keyrings/jenkins-keyring.asc > /dev/null 
    6  echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \   https://pkg.jenkins.io/debian binary/ | sudo tee \   /etc/apt/sources.list.d/jenkins.list > /dev/null
    7  sudo apt-get update 
    8  sudo apt-get install jenkins
    9  sudo systemctl enable jenkins
   10  sudo systemctl start jenkins
   11  sudo systemctl status jenkins
   12  sudo cat /var/lib/jenkins/secrets/initialAdminPassword
   13  history


jenkins installing link - https://www.jenkins.io/doc/book/installing/linux/#debianubuntu








we will configure web hooks in jenkins to automate the build
