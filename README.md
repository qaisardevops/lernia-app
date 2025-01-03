# Lernia-App

Ett exempel på en applikation skriven i Golang.


## Bygga källkoden

cd src
make

För att städa upp: make clean


```
podman build -t lernia:latest . --no-cache
podman run -d -p 8080:8080 lernia:latest
```

