✅ Guaranteed Working Method (Install Jenkins via .deb)

Step 1: Download Jenkins package

wget https://pkg.jenkins.io/debian-stable/binary/jenkins_2.462.3_all.deb

Step 2: Install Jenkins

apt install ./jenkins_2.462.3_all.deb -y

Step 3: Start Jenkins

systemctl daemon-reexec
systemctl start jenkins
systemctl enable jenkins

Step 4: Check status

systemctl status jenkins

Step 5: Get Jenkins password

cat /var/lib/jenkins/secrets/initialAdminPassword
