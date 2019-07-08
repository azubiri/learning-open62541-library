# Beginner Tutorials of ROS

## Table of Contents
1. [Introduction](#intro)
2. [Settings](#set)
3. [Building](#build)

<a name="intro"></a>
## Introduction

This repository is made for learning open62541 library. A library which uses the OPC UA protocol.

<a name="set"></a>
## Settings

### Laptop

OS version: Ubuntu 18.04.2 LTS

### Raspberry Pi

	- Raspberry Pi Model: Model 3b+
	- SD card: microSD 32GB
	- OS version: Raspbian GNU/Linux 10 (buster)
	- Kernel Linux version: 4.19.50-v7+

<a name="build"></a>
## Building

For building any c file:

```sh
$ gcc -I /home/user/path/learning-open62541-library/ -std=c99 src/open62541.c src/any-file.c
```

For instance, if we want to compile laptop-simple-client.c file:

```sh
$ gcc -I /home/user/path/learning-open62541-library/ -std=c99 src/open62541.c src/laptop-simple-client.c
```


