# Constrained Device Application (Connected Devices)

## Lab Module 06

Be sure to implement all the PIOT-CDA-* issues (requirements) listed.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? Establece la conexión con el broker MQTT y gestiona la suscripción y publicación de datos.
Esto permite al dispositivo interactuar con el sistema a través de MQTT.

How does your implementation work?DeviceDataManager utiliza MqttClientConnector para iniciar, suscribirse y gestionar los mensajes.
La clase MqttClientConnector maneja toda la comunicación MQTT con el broker.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/carmenvt7/python-components/tree/labmodule06


### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- 
- 
- 

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- MqttClientConnectorTest
- MqttClientControlPacketTest
- 

EOF.
