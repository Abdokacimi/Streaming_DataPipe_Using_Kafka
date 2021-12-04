# Streaming_DataPipe_Using_Kafka
Streaming workflow


# Scenario
You are a data engineer at a data analytics consulting company. You have been assigned to a project that aims to de-congest the national highways by analyzing the road traffic data from different toll plazas. As a vehicle passes a toll plaza, the vehicle's data like vehicle_id,vehicle_type,toll_plaza_id and timestamp are streamed to Kafka. Your job is to create a data pipe line that collects the streaming data and loads it into a database.

## Objectives
In this assignment you will create a streaming data pipe by performing these steps:

* Start a MySQL Database server.
* Create a table to hold the toll data.
* Start the Kafka server.
* Install the Kafka python driver.
* Install the MySQL python driver.
* Create a topic named toll in kafka.
* Customize a streaming data generator program to steam to toll topic.
* Customize a consumer program to write into a MySQL database table.
* Verify that streamed data is being collected in the database table.

__PS__ : Each row is a record of when a vehicle has passed through a certain toll plaza along with its type and anonymized id.

## Results

Streaming data generator :

![simulator_output](https://user-images.githubusercontent.com/44294643/144728265-35f0a0ed-6b27-4397-a993-8cd4d88634fd.PNG)


Consumer Progrem :

![streaming_reader_code](https://user-images.githubusercontent.com/44294643/144728288-1d9f4bee-4086-4848-bc44-ee2caba72f55.PNG)


Loading Step :

![output_rows](https://user-images.githubusercontent.com/44294643/144728298-0ff0f474-1edf-46a4-bd8c-ee7b64313bee.PNG)

