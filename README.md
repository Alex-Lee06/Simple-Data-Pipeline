# Simple-Data-Pipeline
- *This project will walk you through on creating a data pipeline for Big Data using Hadoop.  You will need to have basic knowledge in Linux, Scala, Spark, NoSQL.  This walk-through will be for 2 or more clusters project.  All computers that is used will have Ubuntu 16-04 OS installed.*  *You will need to follow these steps for all computers.  The Master node **computer that will control all actions will have a different steps.** The slave nodes **computers that will become datanodes will have different steps.**  Please make sure to check that the steps are followed correctly.  The steps will be labeled for each master and slave nodes.  We hope you enjoy this tutorial.*


# Installing Ubuntu 16.04
First, installing Ubuntu as your OS:

To begin Ubuntu install version 16.04 follow the link below.  You will need to know if you can run the 64-bit processor or a 32-bit process.  You can find that information from your system settings.  You will need Bit Torrent for the installation.

- Bit Torrent installation for Windows OS:
  http://www.bittorrent.com/downloads/win

- Bit Torrent installation for MAC OS:
  http://www.bittorrent.com/downloads/mac

- Link to install Ubuntu 16.04
  https://www.ubuntu.com/download/alternative-downloads


# Following along via Github,

First make sure you have a valid Github account

If not, then you can make an account at https://github.com/

​	Installing Github from terminal: 

```
$ sudo apt-get install git
```

​	Cloning the repository to your local: 

```
$ git clone https://github.com/Alex-Lee06/Simple-Data-Pipeline.git
```



# Checking and installing Java

To run Hadoop (or an Apache Big Data service), **YOU WILL NEED JAVA**

To check to see if you have Java installed on your system

​	You can check your Java version by running:

```
$ java -version
```

​	OR, you can run these commands

```
$ java
```

```
$ javac
```

​	*if your receive a usage message for either one, then your Java in installed.*

If you do **NOT** have Java installed then, 

```
$ sudo apt-get install default-jdk
```

And this will download the most recent version of the JDK.
