**Installing Docker**

-----------------------------------------------------------

```

sudo apt-get update
sudo apt install docker.io

```

Add ubuntu user to the docker group:

```

sudo groupadd docker
sudo usermod -aG docker $USER

```

Then, log out and log back and try to run this:

```

docker run hello-world

```

-----------------------------------------------------------