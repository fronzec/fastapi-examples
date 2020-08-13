# Simple REST API using FastAPI

## How to run on Fedora
```
$ podman build -t fastapi .
$ podman images
$ podman run --rm -v $PWD:/srv:z -p 8000:8000 --name fastapi -d fastapi
$ curl http://127.0.0.1:8000
$ podman stop fastapi
```
