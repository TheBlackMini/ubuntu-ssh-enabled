# ubuntu-ssh-enabled

NOTE: THIS IMAGE IS TO BE USED FOR TEST AND LEARNIGN PURPOSES ONLY! NOT TO BE USED IN A PRODUCTION ENVIRONMENT!

SSH Enabled Ubuntu Image for Test and Dev purposes ONLY!

## Use:

Run the container:

Linux: 

```docker run -d theblackmini/ubuntu-ssh-enabled```

Windows:

```docker run -d -P --name <container-name> theblackmini/ubuntu-ssh-enabled```

Reveal the port number

```docker port <container-name>``` 

Identify the Internal IP

```docker inspect <container-id-name>```

SSH

Linux:

```ssh <container-ip>```

Windows:

```ssh localhost:<container-port>```

**Username:** root

**Password:** Passw0rd

Based on : https://docs.docker.com/engine/examples/running_ssh_service/
