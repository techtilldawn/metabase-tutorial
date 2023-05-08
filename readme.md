<h1> Vorraussetzung </h1>

Serverumgebung, Docker, Docker Compose...

<h2> Install Docker & Docker Compose</h2>

<h3> Docker </h3>

```
sudo apt-get update
sudo apt install apt-transport-https curl gnupg-agent ca-certificates software-properties-common -y
```
```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"
```
```
sudo apt install docker-ce docker-ce-cli containerd.io -y
```
```
sudo usermod -aG docker $USER
newgrp docker
```

<h3> Docker Compose </h3>

```
sudo apt update
sudo install docker-compose
```

<h1> Setup </h1>
- Configs, Schritt für Schritt...

<h1> Bonus </h1>
- mit NPM aufsetzten.
