# Docker Registry UI Example

Start the local Docker Registry and UI.

```bash
$ docker-compose up -d
```

As an example, push the docker-registry-ui image to the local Docker Registry.

```bash
$ docker tag buluma/docker-registry-ui localhost/buluma/docker-registry-ui
$ docker push localhost/buluma/docker-registry-ui
The push refers to repository [localhost/buluma/docker-registry-ui]
a504cc7fd96d: Pushed
a28ff545522a: Pushed
eaea6e1c6664: Pushed
f356383db640: Pushed
5f70bf18a086: Pushed
b2d5eeeaba3a: Pushed
latest: digest: sha256:fb91cb0c9f1d4fb874f1ffb854a212f3ae4578b4e64581b53651c50cdeb2496d size: 1573
```

Then you will find the pushed repository 'buluma/docker-registry-ui' in the following URL.
http://localhost/ui/buluma/docker-registry-ui
