This folder contains the code used to make a container nginx applications that use http3, https and http. <br />
The container is deployed within a worker node. Its initialized within a pod in the node, using the code **nginx-pod.yaml**. <br />
The .conf files are used to configure nginx so that it supports the specified application layer protocol (http3, https or http) <br />
The certificates used to make the http3 communication secure is present in the **cert folder** <br />
All the commands used to make the containers are present in **deploy.sh**
