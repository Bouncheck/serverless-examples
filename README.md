# serverless-examples
Code examples for ScyllaDB Cloud Serverless platform.

### gohelloserverless

Once a connection bundle file has been saved on a local disk, run the following:

```bash
cd gohelloserverless
go run main.go -bundle connection-bundle-cluster-name.yaml
```

### jhelloserverless

Once a connection bundle file has been saved on a local disk, run the following:

```bash
cd jhelloserverless
mvn clean compile assembly:single
java -cp target/jhelloserverless-1.0-SNAPSHOT-jar-with-dependencies.jar com.scylladb.JHelloServerless --bundle /path/to/bundle
```
