
# Install-compile-and-run-on-Ubuntu

Before installing any packages, we need to update our list of packages and upgrade them we can do so with following steps:

**1.Update** 

     sudo apt update 

*what update do?* 

apt-get does not install new versions of software, instead it
Updates the package list for upgrades for packages that need upgrading, as well as new packages that have just come to the repositories. It will do this for all of repos and PPAs. From 
http://linux.die.net/man/8/apt-get

**2.upgrade**

     sudo apt upgrade 

*what upgrade do?*

apt-get  upgrade will fetch new versions of packages from apt-get update list and install all packages and their dependencies.


# Installing packages for languages and Running them


## **1. Python**

 Python is pre-installed in most distros,  let’s check if we have it or not:

    python3 --version
If we don’t have it we can install it like this:

    sudo apt install python3

*How to run Python code ?*

    python3 filename.py

## **2. Java Script**
For JavaScript we have to Install nodejs to run JS outside of Browsers:

    sudo apt install npm
For running JS code with
node we can use the command:

    node filename.js

Npm is nodeJs package manger => we use it to
download and install packages… npm installs
nodejs for us… so we can code outside of Browers

## 3. C++
For installing c++ on ubuntu we have to at first isnatall build-essential:

    sudo apt install build-essential

cheeking if we have it installed:

    g++ --version

Installing gcc/g++ compiler:

    sudo apt install g++
How to compile the .cpp file:

    g++ samplefile.cpp –o samplefile

How to run the .cpp file:

    ./samplefile

     
 

## 4. Rust

  Rust or rust-lang is a general-purpose programming language for system-level development projects. Rust is known for its speed, memory efficiency, seamless integration with other languages, and type safety.
  
Cheekking for rust on the system:
 
       rustc -V

Instaling rust:

    sudo apt install rustc

Running rust code:

    rustc main.rs
    ./main

## **6. Java**

For Java we need JDK => Java Development Kit

    sudo apt install default-jdk
For compiling Java code we can use command:

    javac  filename.java
When we compile Java code this gives us a filename.class file with the class name we used in our program we have to run this class to see the result:

    java className
