# URL
~~~
git config -l
~~~
- https://github.com/darcy-it/docker-container.git
    - for update.

# Docker command

## ubuntu20.04
```
sudo docker image build -t ubuntu/only:20.04 --no-cache .
sudo docker images
```
~~~
sudo docker container run -it --rm --name ubuntu20.04 <IMAGE ID>
~~~

## amazonlinux2.0
~~~
sudo docker image build -t linux2/only:2.0.20211223.0 --no-cache .
sudo docker images
~~~
~~~
sudo docker container run -it --rm --name linux2 <IMAGE ID>
~~~
