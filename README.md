
##### downlaod kurento-tutorial-java
```
https://github.com/Kurento/kurento-tutorial-java
https://github.com/Kurento/kurento-tutorial-js
https://github.com/Kurento/kurento-tutorial-node
```


##### https://github.com/Kurento/kurento-tutorial-java/tree/master/kurento-hello-world-recording
```
cd kurento-tutorial-java/kurento-hello-world-recording
```

##### run
```
mvn -U clean spring-boot:run -Dkms.url=ws://localhost:8888/kurento
mvn -U clean spring-boot:run -Dkms.url=ws://3.81.48.139:8888/kurento
```

##### ec2 kms
ssh -i "demo.pem" ubuntu@ec2-3-80-4-195.compute-1.amazonaws.com
##### docker kms
```
docker pull kurento/kurento-media-server
docker run --name kms -d -p 8888:8888 kurento/kurento-media-server
docker run --name kms -d -v ~/kaden/tmp:/tmp -p 8888:8888  kurento/kurento-media-server
docker run --name kms -d -v ~/Desktop/tmp:/tmp -p 8888:8888  kurento/kurento-media-server

##### aws kms
```
https://ec2-100-26-151-26.compute-1.amazonaws.com
```


docker run --name kms -d -v ~/kaden/kurento-tutorial-java/kurento-hello-world-recording/tmp:/tmp -p 8888:8888  kurento/kurento-media-server

sudo docker cp kms:/tmp/HelloWorldRecorded.webm ~/Desktop/HelloWorldRecorded.webm
docker exec -it containerId bash   

docker stop $(docker ps -aq)    
docker rm $(docker ps -aq)    
docker rmi $(docker images -q)
```

https://localhost:8443 
http://3.80.4.195:8080/




##### amount
sshfs ubuntu@ec2-3-80-4-195.compute-1.amazonaws.com:/home/ubuntu/Code/openvidu Code/openvidu -o IdentityFile=/kindom/demo.pem -o allow_other


https://howchoo.com/g/ymmxmzlmndb/how-to-install-sshfs



