# etcd

github addr [https://github.com/kubernets/etcd](https://github.com/kubernets/etcd)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/etcd/raw/master/get-etcd-image.sh

## Arch and Version

- [**amd64** 3.2.18](https://hub.docker.com/r/kubernets/etcd-amd64)

    > docker pull kubernets/etcd-amd64:3.2.18

    > docker tag kubernets/etcd-amd64:3.2.18 gcr.io/google-containers/etcd-amd64:3.2.18 

    > docker rmi kubernets/etcd-amd64:3.2.18
