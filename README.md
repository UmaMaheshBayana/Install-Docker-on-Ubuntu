# Install-Docker-on-Ubuntu

```
curl -fsSL https://get.docker.com -o get-docker.sh
```

```sh get-docker.sh```

```exit```

# Login Again with user

```sudo usermod -aG docker $USER``` 

# To check the Docker Containers

```docker ps -a```

# If you get permission denied execute the below command

```sudo chmod 666 /var/run/docker.sock```

# To start the Docker container

```Docker start ______(enter container ID)```

# To Go inside the container

```docker exec -it ______(container name) /bin/bash```
