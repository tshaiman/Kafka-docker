# kafka-docker
## Docker Compose 

This docker-compose include Zookeeper, a Kafka Broker, and the schema registry.

### Setup your environment 

* Download and install Docker https://www.docker.com/community-edition#/download
* Follow instructions on the link to set up gcloud sdk https://cloud.google.com/sdk/docs/
* If you are running mac add the following to your /etc/hosts


``` 127.0.0.1       localunixsocket```

``` 127.0.0.1       kafka zookeeper ```

 
If you are using windows machine replace localunixsocket with localhost. 

### Launch Images

```
docker-compose up
```

### Access
* Schema Registry can be accessed at: http://localunixsocket:8081/subjects
* Kafka can be accessed at localunixsocket:9092
