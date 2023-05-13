Day 1
=====
![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/691ac5f3-7354-451f-9365-8e5a87545341)
Code 
----
-- Git, github, jira, confluence

Build
----
-- maven, sbt

Test
----
-- junit, selenium

Release
-------
-- Jenkins, codeship

Monitoring
----------
-- Nagios, Splunk, Datadog, prometheus, grafana

Operations
-----------
-- Ansible, Kubernetes, Chef,

Deploy
------
-- DC OS, Docker, aws

```
Tools we are using in this project are 
```
```
-- Spring boot
-- Git
-- Maven
-- Jenkins
-- Splunk
-- Kubernets
-- Ansible
-- Terraform
-- Kafka
-- Aws
-- Docker
```

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/adc48e0a-cba5-4a0e-a68e-939f72b881ba)
This is the process we follow in this project
---

CICD End to end process
----------------------
![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/6b564b2b-b124-44d0-b6dc-61de9a9c2748)

1) requirement of the application we have to take orders and reply with aknowledgments, and do some stuff like Saving, taking, processing the order and send to DB (code complete) used any Source code like git
2) Dev completed the code (IDE - STS) (Now code is available in local machine) ===> sending the code to repo (Like github, gitlab, bitbuket) (Moved to Repo)
3) Bulid the package using maven build tool through jenkins (Plays an imp role in entire CICD process) from the build we got artifact
4) Jenkins will bind with different tools and run the pipeline all other tools like static code analaysis, unit testing, build report, artifact, build and pust image, depoly to kubernets and monitoring.
 
![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/30062315-746b-43c5-962a-7733a02cb05f)

Jenkins will use of these images in the pipeline
------------------------------------------------
6) Code -- Repo -- Jenkins -- Maven (Jenkins integrated with maven) -- maven builds the code in small jar file (Binaries) Here maven converts the code in small files like 10gb to 1gb for example. 
7) The jar files made by jenkins will be send to JFrog (artifacts, binaries, files(wch are less in size like 10 to 30mb are placed) JFrod or Nexus 
8) After the build happens we have static code analysis which is done by sonarQube 
-- Checks duplicate, vulnerabilites, code smells and etc
9) Unit testing -- Dev writes the test his code by some sample test cases Junit test cases
10) Onces the unit testing is done we are sending the artifactor file to the JFrog or Nexus

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/6b3efb4c-5c4e-4e21-8aa5-95dbcbfccda4)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/ce055464-16fd-49ff-b2e4-c59712ea7e16)

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/e0f79b35-d674-459c-9551-98e77386e5b4)

Before sending to K8's (pods)
Here C4 is the JFrog files and now as shown in the blow pictures the files are converted into docker 
The small file wch are send to jfog is converted into Docker container which is Jar/WAR FILE

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/30312491-4619-41ae-a392-82a60ff99515)

Ansible is a tool which tells where to deploy the container, How to deploy, any automations will be done by ansible in deployment

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/28432ebf-1b40-4576-9e13-ebef1299f044)

Here JAR Is converted into container and it is converted into POD and pod is deployed in kubernets by ansible

![image](https://github.com/pavankumar0077/DevOps_Spring_boot_project/assets/40380941/c4458b87-77f5-4b69-b053-178ba80edc16)

Kubernets -- It is env where we deploy our applications wch is scalable, security, relable and etc

















