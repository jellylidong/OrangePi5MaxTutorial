## Install docker desktop

## Install ubuntu docker image

1. According to the official document, let's use ubuntu 22.04
```bash
docker container run -d -it --name ubuntu2204 --rm ubuntu:22.04 
```
2. Log into the container
```bash
docker exec -it ubuntu2204 sh 
```

3. Update and install Python3, git
```bash
apt-get update; apt-get install python3 python3-dev python3-pip; apt-get install git
```

4. Install RKNNToolKit2
```bash
apt-get install libxslt1-dev zlib1g-dev libglib2.0 libsm6 libgl1-mesa-glx libprotobuf-dev gcc 
```