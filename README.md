# Kali

Kali Linux as a docker container.

### Mac/Linux

```
$ docker run --rm -it --user="$(id -u):$(id -g)" --net=none -v "$(pwd):/tmp" thomasleplus/kali bash
```

### Windows

In `cmd`:

```
$ docker run --rm -it --net=none -v "%cd%:/tmp" thomasleplus/kali bash
```

In PowerShell:

```
$ docker run --rm -it --net=none -v "${PWD}:/tmp" thomasleplus/kali bash
```
