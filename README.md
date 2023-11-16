# containers
collection of scripts for working with containers

# Podman scripts for doing some digging

here are some [link for learning](https://github.com/pditommaso/awesome-containers)

[Podman Desktop Companion](https://iongion.github.io/podman-desktop-companion/)

# [Podman Installation](https://podman.io/docs/installation)

```angular2html
$ podman machine init
$ podman machine start

# You can then verify the installation information using:

$ podman info
```

# [Podman Tutorials](https://docs.podman.io/en/latest/Tutorials.html)

```
$ podman run -v $HOME:/tmp  -it fedora  /bin/bash
$ podman run -v $HOME:/tmp --interactive centos:latest  /bin/bash
```
# above runs fedora/centos 'interactively' /bin/bash shell 
