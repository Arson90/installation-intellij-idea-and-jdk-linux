# installation-intellij-idea-and-jdk-linux

## Installation Intellij-IDEA on Ubuntu and other Linux Distribution
### About 
We have a few versions of Intellij-IDEA
* IntelliJ IDEA Community Edition (Free)
* IntelliJ IDEA Ultimate Edition (Paid version with extra features)
* IntelliJ IDEA Educational (Ultimate Edition but free for students and faculty members)

We have a few way to install Intellij-IDEA.

**1. The easiest way to install is using Software Center. Choose the right version and click install.**

![intellij](https://user-images.githubusercontent.com/37801354/149545931-593af621-7d15-48f7-88a9-da76e94b90b3.jpg)

**2. Install using umake**
```
sudo apt-get update
```
```
sudo apt-get install ubuntu-make
```
* Community edition:
```
umake ide idea
```
* Ultimate edition:
```
umake ide idea-ultimate
```
To uninstall:
```
umake -r ide idea
```
or
```
umake -r ide idea-ultimate
```

**3. Install using SNAP**
* Community edition:
```
sudo snap install intellij-idea-community --classic
```
* Educational edition:
```
sudo snap install intellij-idea-educational --classic
```
* Ultimate edition:
```
sudo snap install intellij-idea-ultimate --classic
```

## Installation JDK on Ubuntu and other Linux Distribution
```
sudo apt update
```
* For jdk version 11
```
sudo apt install openjdk-11-jdk
```
