# Download nexus source 

Download source file for your OS from [Sonatype web site](https://www.sonatype.com/download-oss-sonatype) 
or 
```
$ wget https://sonatype-download.global.ssl.fastly.net/nexus/3/nexus-3.23.0-03-unix.tar.gz
```

# Insall nexus
Refer [official documents](https://help.sonatype.com/repomanager3/installation/installation-methods)

## Prerequsites
Nexus Repository Manager requires a Java 8 Runtime Environment (JRE).
```
$ java -version
openjdk version "1.8.0_191"
OpenJDK Runtime Environment (build 1.8.0_191-b12)
OpenJDK 64-Bit Server VM (build 25.191-b12, mixed mode)
```

## Install
Choose any directory to install. 
```
$ tar -xzvf nexus-3.23.0-03-unix.tar.gz
```
You'll see these two directories, `sonatype-work` and `nexus-3.23.0-03`. Just run nexus shell.
```
$ cd nexus-3.23.0-03/bin
$ ./nexus run
```

