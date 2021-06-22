### Env Variable
```
export CLOUDKARAFKA_BROKERS=broker1:9094,broker2:9094,broker3:9094
export CLOUDKARAFKA_USERNAME=<username>
export CLOUDKARAFKA_PASSWORD=<password>
```

### Run

```
git clone 
cd java-kafka-example
mvn clean compile assembly:single
java -jar target/kafka-1.0-SNAPSHOT-jar-with-dependencies.jar
```
