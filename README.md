# TP_RPG_CICD

Commande a lancer ::: 
- docker build -t myjenkins-blueocean:2.462.3-1 .
- docker-compose up -d   
Pour récuperer le password sur la page : http://localhost:8080 il  faut faire la commande :
- docker exec jenkins-blueocean cat /var/jenkins_home/secrets/initialAdminPassword
- Puis récuperer la chaine de characteres donnée et la mettre sur l'IHM