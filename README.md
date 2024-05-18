# My_practice
SETUP:
Taken ubuntu server
Install JAVA 
Install Docker and Jenkins in server
set the port and Add port in SG.
sudo usermod -aG jenkins ubuntu
sudo usermod -aG docker jenkins  --> and logout and login.
start docker and jenkins services --> systemctl start jenkins.service and systemctl start docker.service
 -
Access the console :- Enter Public_IP:PORT (ex:10.24.34.44:8080)
set user name,password, etc,.
install plugins reqired, for demo I installed suggested plugins .
for docker functionality intall docker pipeline plugin. ( Jenkins Manager>plugins/available plugins/docker pipeline.

docker pipeline


This is First Pipeline.

