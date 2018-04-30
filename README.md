# Docker Android container

> Android docker container for testing purposes

## Building

```shell
$ docker build -t hmatalonga/docker-android .    # Only necessary for first build
$ docker run -it --name container-name \         # Choose a container name
-v `pwd`:/usr/src/app \                          # DO NOT change this src path
hmatalonga/docker-android \
/bin/sh -c \
"./gradlew someTask"
```

## License

MIT © [Hugo Matalonga](http://hmatalonga.com)
