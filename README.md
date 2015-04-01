Ubuntu based container with Oracle Java

## Pull Images

Actually this Docker container supports:

- Oracle Java 6
- Oracle Java 7
- Oracle Java 8
- Oracle Java 9

Pull the image.

Oracle Java 6:

```
docker pull oscerd/java:oraclejava6
```

Oracle Java 7:

```
docker pull oscerd/java:oraclejava7
```

Oracle Java 8:

```
docker pull oscerd/java:oraclejava8
```

Oracle Java 9:

```
docker pull oscerd/java:oraclejava9
```

## Run containers

Run containers

Oracle Java 6:

```
docker run --name container_java6 -ti oscerd/java:oraclejava6 /bin/bash
```

Oracle Java 7:

```
docker run --name container_java7 -ti oscerd/java:oraclejava7 /bin/bash
```

Oracle Java 8:

```
docker run --name container_java8 -ti oscerd/java:oraclejava8 /bin/bash
```

Oracle Java 9:

```
docker run --name container_java9 -ti oscerd/java:oraclejava9 /bin/bash
```
