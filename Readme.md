# Spark-Installation

## **Step 1: Verifying Java Installation**

Java installation is one of the mandatory things in installing Spark. Try the following command to verify the JAVA version.

```
$java -version
```
<img width="554" alt="Screenshot_2023-02-22_at_4 27 57_PM" src="https://user-images.githubusercontent.com/88190547/224557614-9249d278-ee80-4594-ba1a-a5e008ed8939.png">


## **Step 2: Verifying Scala installation**

You should Scala language to implement Spark. So let us verify Scala installation using following command.

```
$scala -version

```

If Scala is already installed on your system, you get to see the following response −
<img width="550" alt="Screenshot_2023-02-22_at_4 28 31_PM" src="https://user-images.githubusercontent.com/88190547/224557640-01e92f07-8558-40a9-8f05-d72be7f3446e.png">


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
<img width="614" alt="Screenshot_2023-02-22_at_4 35 00_PM" src="https://user-images.githubusercontent.com/88190547/224557693-157e8d31-cb27-4be1-8e4a-db83f8a1d890.png">


### **Setting up the environment for Spark**

Add the following line to ~**/.bashrc** file. It means adding the location, where the spark software file are located to the PATH variable.

```
export PATH=$PATH:/usr/local/spark/bin

```
<img width="591" alt="Screenshot_2023-02-22_at_4 36 55_PM" src="https://user-images.githubusercontent.com/88190547/224557713-69ef4980-514e-4e1e-931a-63afb7a5fa66.png">

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

<img width="1343" alt="Screenshot_2023-02-22_at_4 42 02_PM" src="https://user-images.githubusercontent.com/88190547/224557746-1fdec0b2-6f39-46a6-9c4d-ab8bb89feaeb.png">
