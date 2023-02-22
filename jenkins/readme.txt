docker run -u root -itd -p 2080:8080 -p 50000:50000 --name jenkins --privileged=true  -v /home/data/jenkins_home:/var/jenkins_home  jenkins/jenkins:lts
