
##### downlaod kurento-tutorial-java
```
git clone https://github.com/Kurento/kurento-tutorial-java
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




##### docker 
```
sudo docker cp kms:/tmp/HelloWorldRecorded.webm ~/Desktop/HelloWorldRecorded.webm
```

https://localhost:8443

