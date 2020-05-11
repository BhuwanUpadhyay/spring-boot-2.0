# Chapter - 1.1. Tools Set

## Installation

Spring Boot needs `java`, `maven` and `springboot` to build the application, [sdkman](https://sdkman.io/install) can help us for quick setup of these tools the process is straight forward:

```
$ curl -s "https://get.sdkman.io" | bash
$ source "$HOME/.sdkman/bin/sdkman-init.sh"
$ sdk install java
$ sdk install maven
$ sdk install springboot
```

Once you have finished the installation then you can verify:

```bash
$ sdk version

SDKMAN 5.7.4+362

$ java -version

openjdk version "14" 2020-03-17
OpenJDK Runtime Environment (build 14+36-1461)
OpenJDK 64-Bit Server VM (build 14+36-1461, mixed mode, sharing)

$ mvn -version

Apache Maven 3.6.3 (cecedd343002696d0abb50b32b541b8a6ba2883f)
Maven home: /home/pc/.sdkman/candidates/maven/current
Java version: 14, vendor: Oracle Corporation, runtime: /home/pc/.sdkman/candidates/java/14.0.0-open
Default locale: en_US, platform encoding: UTF-8
OS name: "linux", version: "5.3.0-51-generic", arch: "amd64", family: "unix"


$ spring --version
Spring CLI v2.2.7.RELEASE
```



