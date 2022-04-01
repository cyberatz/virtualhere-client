# virtualhere-client

## 1. Built it locally on the machine you want to run it
docker build -t virtualhere github.com/virtualhere/docker


## 2. Run the container
docker run -it --rm virtualhere ash

## 3. run client
./vhclientx86_64 -t "LIST"

