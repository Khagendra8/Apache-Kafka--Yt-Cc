Code with Durgesth YT link = https://youtu.be/ei6fK9StzMM

Command to create topic in kafka
====================================

CREATE TOPIC >>>            kafka-topics.bat --create --topic location-update-topic --bootstrap-server localhost:9092 --replication-factor 1 --partitions 3
OPEN CONSUMER CONSOLE >>>   kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic location-update-topic --from-beginning
DELETE THE KAFKA TOPIC >>>  kafka-topics.bat --bootstrap-server localhost:9092 --delete --topic location-update-topic

Producer POST endpoint = http://localhost:8080/location/update