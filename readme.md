<h1> Vorraussetzung </h1>

Serverumgebung, Docker, Docker Compose...

<h2> Install Docker & Docker Compose</h2>

<h3> Docker </h3>

```
sudo apt-get update 
```
```
sudo apt install apt-transport-https curl gnupg-agent ca-certificates software-properties-common -y
```
```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```
```
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"
```
```
sudo apt install docker-ce docker-ce-cli containerd.io -y
```
```
sudo usermod -aG docker $USER
```
```
newgrp docker
```
(disconnect from ssh session, to activate a new session with your user in the docker group)

<h3> Docker Compose </h3>

```
sudo apt update
```
```
sudo apt install docker-compose -y
```

<h1> Setup </h1>
- Configs, Schritt für Schritt...
- Create a folder

```
mkdir metabase
```
Copy the docker compose file into it (or copy the content)

```
touch docker-compose.yml && touch metadb_password.txt
```
```
vim docker-compose.yml
```
```
vim metadb_password.txt
```
Start your container with docker compose
```
docker-compose up -d
```

<h1> Bonus </h1>
- mit NPM aufsetzten.


--- TEST
