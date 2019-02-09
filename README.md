
# Docker web stack with Wordpress , MariaDB and Nginx-Pagespeed

This Repo is for Web application stack with Wordpress , MariaDB and Nginx-Pagespeed 

---

**Note** : First should edit `Secrets` files in ./secrests .

---
For use from this Repo you should have one of these:

- Docker Swarm ( Recommend )

or

- Docker-Compose

## Set up your swarm

```
docker swarm init [OPTIONS]
```
for more info see [Docker Swarm Doc](https://docs.docker.com/engine/reference/commandline/swarm_init/)

#  Deploy stack
for deploy stack use 

```
docker stack deploy -c docker-compose.yml <STACK NAME>
```

**NOTE**: for update stack just need to edit files and redeploy stack.

for check stack services status
```
docker stack services <STACK NAME>
```

for remove stack
```
docker stack rm <STACK NAME>
```