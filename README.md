## Install docker
Ubuntu：https://docs.docker.com/install/linux/docker-ce/ubuntu/

## Run

* Go to the dir
```
cd demo1
```

* Build image
```
docker image build -t docker-demo .
```

* Start docker instance
```
docker container run -p 8000:3000 -it docker-demo /bin/bash
```

* Open on the browser
```
https://localhost:8000
````



