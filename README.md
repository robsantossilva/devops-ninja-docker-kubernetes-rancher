<center>
<a href="https://github.com/jonathanbaraldi/devops-ninja-multicloud-multicluster-pt/stargazers">
	<img src="https://img.shields.io/github/stars/jonathanbaraldi/devops-ninja-multicloud-multicluster-pt" alt="Stars Badge"/>
</a>
<a href="https://github.com/jonathanbaraldi/devops-ninja-multicloud-multicluster-pt/network/members">
	<img src="https://img.shields.io/github/forks/jonathanbaraldi/devops-ninja-multicloud-multicluster-pt" alt="Forks Badge"/>
</a>
<a href="https://github.com/jonathanbaraldi/devops-ninja-multicloud-multicluster-pt/pulls">
	<img src="https://img.shields.io/github/issues-pr/jonathanbaraldi/devops-ninja-multicloud-multicluster-pt" alt="Pull Requests Badge"/>
</a>
<a href="https://github.com/jonathanbaraldi/devops-ninja-multicloud-multicluster-pt/issues">
	<img src="https://img.shields.io/github/issues/jonathanbaraldi/devops-ninja-multicloud-multicluster-pt" alt="Issues Badge"/>
</a>
<a href="https://github.com/jonathanbaraldi/devops-ninja-multicloud-multicluster-pt/graphs/contributors">
	<img alt="GitHub contributors" src="https://img.shields.io/github/contributors/jonathanbaraldi/devops-ninja-multicloud-multicluster-pt?color=2b9348">
</a>
<a href="https://github.com/jonathanbaraldi/devops-ninja-multicloud-multicluster-pt/blob/master/LICENSE">
	<img src="https://img.shields.io/github/license/jonathanbaraldi/devops-ninja-multicloud-multicluster-pt?color=2b9348" alt="License Badge"/>
</a>
</center>


![DevOps Ninja - Multicloud-Multicluster](doc/img/logo.png)

# UDEMY

![Udemy](doc/logos/udemy-small.png)

Este repositório pertence ao meu curso da Udemy, DevOps Ninja: Multicloud-Multicluster:

https://www.udemy.com/course/multicloud-multicluster-k8s-rancher-traefik-cockroachdb/?referralCode=9AE9624A95C83529212F

Acesse e aproveite o cupom de desconto para usuários do GitHub!


----------------------------------------------------------------

```bash
#!/bin/bash
curl https://releases.rancher.com/install-docker/19.03.sh | sh
usermod -aG docker ubuntu
```

```bash
sudo su
apt-get install git -y
curl -L "https://github.com/docker/compose/releases/download/1.25.5/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose
ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
```

```bash
cd /home/ubuntu
git clone https://github.com/robsantossilva/devops-ninja-docker-kubernetes-rancher
cd devops-ninja-docker-kubernetes-rancher/app
```

```bash
cd redis
docker build -t robsantossilva/redis:devops .
```