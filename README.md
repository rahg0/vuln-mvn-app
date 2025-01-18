# vuln-mvn-project

## Dep list
```sh
$ mvn dependency:tree
[INFO] Scanning for projects...
[INFO]
[INFO] -------------------< com.github.rahg0:vuln-mvn-app >--------------------
[INFO] Building vuln-mvn-app 1.0
[INFO] --------------------------------[ jar ]---------------------------------
[INFO]
[INFO] --- maven-dependency-plugin:2.8:tree (default-cli) @ vuln-mvn-app ---
[INFO] com.github.rahg0:vuln-mvn-app:jar:1.0
[INFO] +- junit:junit:jar:3.8.1:test
[INFO] +- com.google.guava:guava:jar:31.0.1-jre:compile
[INFO] |  +- com.google.guava:failureaccess:jar:1.0.1:compile
[INFO] |  +- com.google.guava:listenablefuture:jar:9999.0-empty-to-avoid-conflict-with-guava:compile
[INFO] |  +- com.google.code.findbugs:jsr305:jar:3.0.2:compile
[INFO] |  +- org.checkerframework:checker-qual:jar:3.12.0:compile
[INFO] |  +- com.google.errorprone:error_prone_annotations:jar:2.7.1:compile
[INFO] |  \- com.google.j2objc:j2objc-annotations:jar:1.3:compile
[INFO] +- com.google.protobuf:protobuf-java:jar:3.16.0:compile
[INFO] \- org.springframework:spring-webmvc:jar:6.0.0:compile
[INFO]    +- org.springframework:spring-aop:jar:6.0.0:compile
[INFO]    +- org.springframework:spring-beans:jar:6.0.0:compile
[INFO]    +- org.springframework:spring-context:jar:6.0.0:compile
[INFO]    +- org.springframework:spring-core:jar:6.0.0:compile
[INFO]    |  \- org.springframework:spring-jcl:jar:6.0.0:compile
[INFO]    +- org.springframework:spring-expression:jar:6.0.0:compile
[INFO]    \- org.springframework:spring-web:jar:6.0.0:compile
[INFO]       \- io.micrometer:micrometer-observation:jar:1.10.0:compile
[INFO]          \- io.micrometer:micrometer-commons:jar:1.10.0:compile
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  1.933 s
[INFO] Finished at: 2025-01-18T14:17:13Z
[INFO] ------------------------------------------------------------------------
```

## Clone the Repo

## Compile
```sh
$ mvn compile
```

## Package
```sh
$ mvn package
```

## Install to local repo
```sh
$ mvn install
```
