This project is a basic representation of building IoT scenario with IBM Bluemix, IBM Watson services. This project consists of different blocks. The primary business scenario is collecting the live status of the storage bins in a warehouse.

1. Sensor Node 
  Ultrasonic sensor and motion sensor with arduino to calculate the bin status. The smart logic implemented in the sensor node to optimize the bin status collection.

2. Client Node 
  Gateway node to collect data from sensor nodes and act as a hub to push all the sensors data to IBM Bluemix IoT services

3. Server Node 
  Computing the historical and real-time device data, smart algorithm to intelligent calculation for efficient business processing.

This is the code repository of Server node in IBM Bluemix. The platform in server node is Node-RED.
