hms-jdk8
=============

This image is the oracle [jdk8][jdk8] base. It comes from [hms-base][hms-base].

## Build

```
docker build -t rawmind/hms-jdk8:<version> .
```

## Versions

- `1.8.112` [(Dockerfile)](https://github.com/rawmind0/hms-jdk8/blob/1.8.112/Dockerfile)


## Usage

To use this image include `FROM rawmind/hms-jdk8` at the top of your `Dockerfile`. 

[hms-base]: https://github.com/rawmind0/hms-base/
[jdk8]: http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html