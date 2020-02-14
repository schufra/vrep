Example for Kafka Usage
===========
#### Description
The data generator generates arbitrary data and passes it to the Kafka producer.
The Kafka consumer reads the data and writes it to a terminal.
You can see the generated data by opening the UI of the terminal operator.

#### Prerequisites
* You need a running Kafka broker and Zookeeper.

#### Configure and Run the Graph
Follow the steps below to run the example from the Data Pipeline UI:

1. In the left panel, select the "Graphs" tab and navigate to com/sap/demo/kafka.

2. Check the configuration of the "producer (20fb)" node: brokers

3. Check the configuration of the "consumer (1h7j)" node: zookeepers

4. In the tool bar, select "Run" (play button).

5. The "Status" panel indicates if the graph is running.

6. Use the context menu "Open UI" of the "terminal (z8d)" node to open the terminal.

7. The terminal opens and you see the generated data.

<br>
<div class="footer">
   &copy; 2019 SAP SE or an SAP affiliate company. All rights reserved.
</div>
