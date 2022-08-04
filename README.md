# helm lab

kubernetes and helm for a demo guestbook application

#### prerequisites:
docker, minikube, kubectl and helm installed locally

#### deploy client, api, and DB just by:
```shell
$ helm install demo-guestbook guestbook
```

add to `/etc/hosts`:
```shell
# minikube ip
192.168.49.2 client.local
192.168.49.2 api.local
```

see the local app live at: http://client.local/

#### remove all by:
```shell
$ helm uninstall demo-guestbook
```