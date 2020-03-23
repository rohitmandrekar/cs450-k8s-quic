This directory contains the code used to make container comprising of nginx applications that use http3, https and http. <br />
The container is deployed within a worker node. Its initialized within a pod in the node, using the code in the file **nginx-pod.yaml**. <br />
The .conf files are used to configure nginx so that it supports the specified application layer protocol (http3, https or http) <br />
The certificates used for the http3 communication secure are present in the **cert folder** <br /> and **gen_certs.sh** <br /> file comprises of commands to generate the certificates

All the commands used to deploy the containers are present in **deploy.sh**
