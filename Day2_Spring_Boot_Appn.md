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

```maven clean install -DskpTest 
```
----  This command is used to build the maven package with skipping the test cases

STEPS TO FOLLOW
===============
1) Step 1 -- Convert the Spring boot application into Jar file by using Maven build tool
2) Step 2 -- Convert the Jar file into Docker image -- Using docker file
3) 




