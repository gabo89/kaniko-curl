# kaniko-curl

building

```
sudo docker build . -t <repo>/kaniko-image:basev1
```

pushing
```
sudo docker push <repo>/kaniko-image:basev1
```

testing
```
sudo docker run -it --entrypoint "curl" <repo>/kaniko-image:basev1
```
