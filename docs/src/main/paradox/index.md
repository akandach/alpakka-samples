# Alpakka Samples

### @extref:[Fetch CSV via HTTP and publish to Kafka](http-csv-to-kafka:index.html)
This example uses Akka HTTP to send the HTTP request and Akka HTTP's JSON support to convert the map into a JSON structure which gets published to a Kafka topic.

### @link:[Amazon SQS](https://github.com/akka/alpakka-samples/tree/master/alpakka-sample-sqs-java) { open=new }
Listen to an Amazon SQS topic, enrich the message via calling an actor, publish a new message to SQS and acknowledge/delete the original message. (Java only)

### @link:[MQTT topic triggers file download which is uploaded to AWS S3](https://github.com/akka/alpakka-samples/tree/master/alpakka-sample-mqtt-http-to-s3-java) { open=new }

Listen to a MQTT topic, download from the URL passed in the received message, and upload the data from that address to AWS S3. (Java only)