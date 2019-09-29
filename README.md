# StopFire-DataStream
StoFire Data Streaming using Apache Kafka, Apache Spark Streaming and MongoDB

StopFire is a campaign started by Monash University to predict and stop the fire in
Victorian cities. They have employed sensors in different cities of Victoria and have
collected a large amount of data. The data is so big that their techniques have failed to
provide the results on time to predict fire. They have hired us as the data analyst to
migrate their data to the NoSQL database (MongoDB). They want us to analyse their data
and provide them with results. In addition, they want us to build an application, a
complete setup from streaming to storing and analyzing the data for them using Apache
Kafka, Apache Spark Streaming and MongoDB.

Firstly I have loaded the data into MongoDB and found few insights of the data (Assignment_TaskA_B).
Further, I have implemented multiple Apache Kafka producers to simulate the real-time
streaming of the data which will be processed by Apache Spark Streaming client and
then inserted into MongoDB (Task C). The overall system architecture you will be developing is
shown in the figure below. 

