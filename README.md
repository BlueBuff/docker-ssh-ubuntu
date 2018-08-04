  

This is dockerfile build docker image file ,
first:

```
cat ~/.ssh/id_rsa.pub > authorized_keys
```

second:

> docker build -t <container-image-name><tag-name> <dockerfile-path>

```
docker build -t sshd:ubuntuV14 .
```

last:

```
docker run -d -P <image-id>
```

> thanks you，bye .


