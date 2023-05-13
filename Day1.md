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
3) Bulid the package using maven build tool through jenkins (Plays an imp role in entire CICD process)
4) Jenkins will manage all other tools like static code analaysis, unit testing, build report, artifact, build and pust image, depoly to kubernets and monitoring
5) 











