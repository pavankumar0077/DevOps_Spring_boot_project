Project Structure
==================
![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/ab728695-fc38-4cd3-845f-797ede0a3ccb)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/854e1556-e776-445e-a20e-49df75fe61f6)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/56a934d4-c665-495f-9966-269ac506689b)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/9933f266-bd29-4c05-8198-6660daaafc55)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/e5969d02-3cec-4c95-a964-80d1c5addb37)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/e43826ba-937c-4488-b3f2-7ca453dea73c)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/919c1dbe-ae31-4fc3-9417-315be0755630)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/67091987-533a-4963-9bc4-c958cc2fec15)

Kubernets manifest files to create pods
=======================================
![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/3c02f292-36be-4c90-bf87-272f93f0036e)

From these kubernets files dynamic db values are comming in application.properties file

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/f7c611e0-d61b-4e4f-8f9d-6b9ba0539782)

Kubernetes main contains 4 things
==================================
![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/192fe036-3e73-4d5d-8979-8a331e01c5e1)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/aa9cfea0-09a2-4e04-ab59-778edbc5ebcd)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/1baedb7b-a7fa-412c-973a-1bff21e1b112)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/41490927-56ea-49e5-b723-d76c48cc47d3)
FROM HERE WE ARE GETTING VALUES OF MYSQL DB to App.yml file

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/172df000-0c7d-4f44-b906-ed9ccec12f9f)

DAO CLASS
---
![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/dbd770ec-50cd-424e-9f8e-52b30fe09a09)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/f43df7b5-7016-4532-b64f-df0f813389d6)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/6d6f8c4c-737e-407b-86bc-72aafe735cfa)

KUBERNETES ARCHITECRE
=====================

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/9c72caed-fd97-405b-ad63-849b4b5a458b)


![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/fb4b1797-e75a-4f10-8789-7e5ee223ba29)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/f2b7328f-14e1-4a95-b090-502ce7b487b9)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/c4c4a3d1-88f0-4fba-af4c-c9d96fbbb0be)

In spring boot application if we want maven package name as short name (Ex : SNAPSHOT to any name )
Then add these line in pom.xml file
![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/d9e4d988-9428-4c88-ad56-9b1a1cc2bceb)


mvn clean install -DskpTest 

----  This command is used to build the maven package with skipping the test cases

STEPS TO FOLLOW
===============
1) Step 1 -- Convert the Spring boot application into Jar file by using Maven build tool
2) Step 2 -- Convert the Jar file into Docker image -- Using docker file
3) Step 3 -- Convert the docker image into pod -- Using kubernetes manifest file
4) ![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/c7f0441b-596c-422b-8c3c-3f1e410c05be)
5) ![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/f2a9524e-3a96-4a66-be6c-ff107b99b1fb)
6) ![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/d6f0da3a-0b90-4733-8831-c733d474220e)
7) kubernets file for springboot application : ![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/f71ea0de-f8fb-4b33-9cb1-7ae3c3d4da53)
8) Types of kind in kubernets file : ![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/e5d4b903-b65a-4d16-8ee6-0ac6c5ace2a8)
9) Pod is container internally (Docker image) ![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/bc2364c7-511c-4846-902d-be502c150025)
10) ![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/46ec0934-99bd-4a3a-8835-30be30b5c59f)
11) Docker file port number and kubernetes manifest file application spec - port should match
12) ![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/8ccbc90a-ba6e-4fb1-9a1f-82d91048f626)
13) ![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/7fc29bb7-28f8-4552-b077-dc49d78b7766)
12 and 13 in 12th image we are setting evn values for the application.yml file -- Here container is hitting with external values
14) In kubernetes When we hit the rest endpoint 1st it will go to service pod and then it will go to actual application pod
15) In Front of the application pod we have service pod ![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/810d1f36-cd7e-4327-8804-6628be1ab13e)
16) This is service pod to application pod is done by using selector lable ![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/6dc7c95c-2809-45b4-93b9-9c219e6224a0)
17) Here service pod port is 8080 and application target port is 8080 when request comes to service pod it will redirect to java application pod
18) ![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/e57240ee-777f-4a68-a15e-749eeae0b989)
19) DB manifest file ![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/44a4a98b-6cee-4eb7-a96e-04abd9b76a1f)
20) Here we are asking for memory allocation for kubernetes for DB persistence volume
21) ![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/6135f716-1951-40bc-b45e-ba8f08c823e3)
22) Store the values in secret files recommeded

--------------------------------------
IN one picture  ( MAIN IMPLEMENTATION)
--------------------------------------
![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/cdba20c1-f786-43e5-a261-b3ac78e643fd)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/327ca7a9-9e19-4ad7-b826-cc73b6a83df3)

Step1 ) After connecting to the --> Connect as root user 
``` 
    sudo su
```
Step2) Update the packages
```
    yum update -y 
``` 
Here -y is used to type yes/Y to update the packages

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/84b2cf92-c17c-4282-a6fc-fb1bd21242e8)

step3) Install docker
![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/68b5880d-8b54-411d-80fb-9525e18279fd)

```
    amazon-linux-extras install docker
```
Check docker version
```
    docker -v
```
Step5) Start docker as service
![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/4c7775f7-13a0-45f3-9349-207025c226f9)
``` systemctl start docker
    systemctl stop docker
    systemctl status docker
    systemctl restart docker
    systemctl enable docker
```
Step6) Install Git and conntrack
![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/cfd2b2a6-687a-4261-833a-21ad38debcc5)

Conntrack is software needed for the kubernetes to run (manikube)
```
    yum install conntrack -y
```
```
    yum install git -y
```
Step 7) Installing k8's or Kubernets
Minikube is the platform to start kubernets
![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/04805c94-2c2d-4b21-9588-1ef720beecf0)

Download minikube
```
    curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
```
Here -LO -- O means output

Install minikube
```
   sudo install minikube-linux-amd64 /usr/local/bin/minikube
```

Step 8) Start Minikube
![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/4664e3b2-c47a-4355-ae04-112545b1d3ca)

Here we are using docker as a driver
In windows we use docker or hyper v as a driver
```
    /usr/local/bin/minikube start --force --driver=docker
```
```
    /usr/local/bin/minikube version
```












