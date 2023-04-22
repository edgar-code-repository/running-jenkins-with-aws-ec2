**Installing Jenkins**

-----------------------------------------------------------

Take a look at this URL before installing Jenkins with apt-get:

https://www.jenkins.io/blog/2023/03/27/repository-signing-keys-changing/

```

sudo apt update
sudo apt install jenkins -y

```

Then verify if Jenkins started successfully:

```

sudo systemctl status jenkins

```

-----------------------------------------------------------