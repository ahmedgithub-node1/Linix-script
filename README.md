sudo yum update -y
sudo amazon-linux-extras install java-openjdk11 -y
sudo wget -o /etc/yum.repos.d/jenkins.repo \
sudo rpm --import https"//pkg.jenkins.io/redhat-stable/jenkins.io.key
sudo yum install jenkins -y
sudo systemctl start jenkins
