APT Mirror container
====================

Run apt-mirror inside a Docker container

Requirements:

* Docker

Build image
-----------
```
docker build -t "apt-mirror-service" .
```

Run manually
------------
```
sudo ./run-apt-mirror
```

Run once a day automatically
----------------------------
```
sudo cp run-apt-mirror /etc/cron.daily/
```

Start nginx
-----------
In order to make the mirror available, you need an HTTP server serving the mirror
```
sudo ./run-nginx
```
Docker will keep it up even after a reboot
