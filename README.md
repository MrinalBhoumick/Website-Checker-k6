Record the HAR File for any Website from Network tab.

Import .har file in this folder.

Install npm install globally har-to-k6 package .

Run the Command : 

har-to-k6 <filename>.har -o k6_script.js

Ensure Docker is Running if on Window Check Docker Desktop:

Status  : Running.

If on Linux :

sudo systemctl status docker

Status : Active (Running)

First Login to Docker Hub

docker login

-> User Name : xxxx

-> Password :  xxx

Build Docker Image :

docker build -t k6-ubuntu .


Run Docker Image :

docker run --rm k6-ubuntu

`` Note : har-to-k6 npm package must be installed  in the directory .
          If not installed install har-to-j6 library.

          Command:

          " npm install --global har-to-k6 "
