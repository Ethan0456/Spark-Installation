# Spark-Installation

## **Step 1: Verifying Java Installation**

Java installation is one of the mandatory things in installing Spark. Try the following command to verify the JAVA version.

```
$java -version
```

![Screenshot 2023-02-22 at 4.27.57 PM.png](Spark-Installation%20ab0bf90485384942830037ab3036a619/Screenshot_2023-02-22_at_4.27.57_PM.png)

## **Step 2: Verifying Scala installation**

You should Scala language to implement Spark. So let us verify Scala installation using following command.

```
$scala -version

```

If Scala is already installed on your system, you get to see the following response −

![Screenshot 2023-02-22 at 4.28.31 PM.png](Spark-Installation%20ab0bf90485384942830037ab3036a619/Screenshot_2023-02-22_at_4.28.31_PM.png)

# If Scala is not Installed

> **Step 1: Downloading Scala**
> 

> Download the latest version of Scala by visit the following link [Download Scala](http://www.scala-lang.org/download/). For this tutorial, we are using scala-2.11.6 version. After downloading, you will find the Scala tar file in the download folder.
> 

> **Step 2: Installing Scala**
> 

> Follow the below given steps for installing Scala.
> 

> **Extract the Scala tar file**
> 

> Type the following command for extracting the Scala tar file.
> 

> $ tar xvf scala-2.11.6.tgz
> 

> **Move Scala software files**
> 

> Use the following commands for moving the Scala software files, to respective directory **(/usr/local/scala)**.
> 

> $ su –
Password:
# cd /home/Hadoop/Downloads/
# mv scala-2.11.6 /usr/local/scala
# exit
> 

> **Set PATH for Scala**
> 

> Use the following command for setting PATH for Scala.
> 

> $ export PATH = $PATH:/usr/local/scala/bin
> 

> **Verifying Scala Installation**
> 

> After installation, it is better to verify it. Use the following command for verifying Scala installation.
> 

> $scala -version
> 

> If Scala is already installed on your system, you get to see the following response −
> 

> Scala code runner version 2.11.6 -- Copyright 2002-2013, LAMP/EPFL
> 

## **Step 5: Downloading Apache Spark**

Download the latest version of Spark by visiting the following link [Download Spark](https://spark.apache.org/downloads.html). For this tutorial, we are using **spark-3.2.3-bin-hadoop3.2** version. After downloading it, you will find the Spark tar file in the download folder.

```jsx
wget [https://dlcdn.apache.org/spark/spark-3.2.3/spark-3.2.3-bin-hadoop3.2.tgz](https://dlcdn.apache.org/spark/spark-3.2.3/spark-3.2.3-bin-hadoop3.2.tgz)
```

## **Step 6: Installing Spark**

Follow the steps given below for installing Spark.

### **Extracting Spark tar**

The following command for extracting the spark tar file.

```
$ tar xvf spark-3.2.3-bin-hadoop3.2.tgz
```

### **Moving Spark software files**

The following commands for moving the Spark software files to respective directory **(/home/hadoop/spark)**.

```
# mv spark-3.2.3-bin-hadoop3.2 /usr/local/spark
# cd /home/Hadoop/Downloads/
# mv spark-3.2.3-bin-hadoop3.2 spark
# ex
```

![Screenshot 2023-02-22 at 4.35.00 PM.png](Spark-Installation%20ab0bf90485384942830037ab3036a619/Screenshot_2023-02-22_at_4.35.00_PM.png)

### **Setting up the environment for Spark**

Add the following line to ~**/.bashrc** file. It means adding the location, where the spark software file are located to the PATH variable.

```
export PATH=$PATH:/usr/local/spark/bin

```

![Screenshot 2023-02-22 at 4.36.55 PM.png](Spark-Installation%20ab0bf90485384942830037ab3036a619/Screenshot_2023-02-22_at_4.36.55_PM.png)

Use the following command for sourcing the ~/.bashrc file.

```
$ source ~/.bashrc

```

## **Step 7: Verifying the Spark Installation**

Write the following command for opening Spark shell.

```
$spark-shell

```

If spark is installed successfully then you will find the following output.

![Screenshot 2023-02-22 at 4.42.02 PM.png](Spark-Installation%20ab0bf90485384942830037ab3036a619/Screenshot_2023-02-22_at_4.42.02_PM.png)