Ubuntu based container with Oracle Java

## Pull Images

Actually this Docker container supports:

- Oracle Java 6
- Oracle Java 7
- Oracle Java 8
- Oracle Java 9
- OpenJDK 7

Pull the image.

Oracle Java 7:

```
docker pull oscerd/java
```

Oracle Java 6:

```
docker pull oscerd/java:oraclejava6
```

Oracle Java 8:

```
docker pull oscerd/java:oraclejava8
```

Oracle Java 9:

```
docker pull oscerd/java:oraclejava9
```

Open JDK 7:

```
docker pull oscerd/java:openjdk7
```

## Run containers

Run containers

Oracle Java 7:

```
docker run --name container_java7 -ti oscerd/java /bin/bash
```

Oracle Java 6:

```
docker run --name container_java6 -ti oscerd/java:oraclejava6 /bin/bash
```

Oracle Java 8:

```
docker run --name container_java8 -ti oscerd/java:oraclejava8 /bin/bash
```

Oracle Java 9:

```
docker run --name container_java9 -ti oscerd/java:oraclejava9 /bin/bash
```

Open JDK 7:

```
docker run --name container_openjdk7 -ti oscerd/java:openjdk7 /bin/bash
```
