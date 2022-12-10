<p align="center">
	<img width="90%" src="./res/thumbnail.png"/>
</p>

## Table of contents
* [Introduction](#introduction)
* [Install](#install)
  * [Linux](#linux)
  * [Windows](#windows)

## Introduction
This is a collection of all projects related to the [avm virtual machine](https://github.com/avm-collection/avm)

## Install

### Linux
Install the projects
```sh
$ git clone https://github.com/avm-collection/installer
$ cd installer
$ make && make install
```

Verify the installation
```sh
$ avm -v
$ anasm -v
```

### Windows
Windows is not yet fully supported, but you can use [WSL](https://learn.microsoft.com/en-us/windows/wsl/)
