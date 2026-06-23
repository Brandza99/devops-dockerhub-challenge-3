#Ovo je samo test 

Projekat radi da testira da li je internet stranica u redu , DNS (Domain name system),URL i port.

#Projekat se sastoji od nekoliko fajlova

 - Dockerfile
 - docker-compose.yml
 - README.md
 - .github/workflows
 - health-check.sh (skriptra za proveru)

#Koriscenje Docker-a

Docker se koristi tako sto prvo kreirate vas image komandom: - docker build  kasnije
                                                             
                                                             - docker run
Docker compose se koristi kucanjem komande: - docker compose up -d (compose se pokrece u pozadini a terminal ostaje slobodan)
                                            - docker compose down (compose se gasi i automatski se brisu containeri)

#Health-check.sh proverava da li je vas internet stranica,dns,port i Url u redu.

#GitHub Actions workflow radi kao automatizacija (CI/CD) izmedju Githuba i DockerHub-a

#Docker Hub image koji  je napravljen je  brandza99/devops-dockerhub-challenge-3


Nadam se da vam je ovo pomoglo 


