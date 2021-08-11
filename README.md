# openjdk_AESBench
This is just a spin-off of Crypto microbenchmarks from OpenJDK.  The goal is to build them using jdk8u and compare performance veritically among different versions of JDKs. I keep code intact but only comment out chacha20 which is inavailable in jdk8u. 

## Prerequisite
 Maven
> sudo apt install maven

## Build
> mvn clean verify

## Run
> java -jar ./target/benchmarks.jar [jmh parameters]
