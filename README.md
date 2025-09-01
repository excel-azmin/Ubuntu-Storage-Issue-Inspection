# Ubuntu-Storage-Issue-Inspection

```
df -h
docker system df
sudo du -h --max-depth=1 /var/lib/docker | sort -hr
docker ps -a --size

sudo du -h --max-depth=1 /var/lib/docker | sort -hr

cd /var/lib/docker
sudo du -h --max-depth=1

sudo du -h --max-depth=1 /var/lib/docker/containers | sort -hr | head -20
sudo du -h --max-depth=1 /var/lib/docker/overlay2 | sort -hr | head -20


sudo du -sh /var/lib/docker/containers/* | sort -hr | head -20


sudo ls -lh /var/lib/docker/containers/{change the container id}/*.log




```
