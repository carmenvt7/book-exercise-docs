# Gateway Device Application (Connected Devices)

## Lab Module 10

Be sure to implement all the PIOT-GDA-* issues (requirements) listed.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? Añadi soporte para autenticación y conexión segura mediante TLS, delegando la suscripción a topics directamente en MqttClientConnector.
Además, el GDA analiza datos de humedad recibidos y envía comandos ActuatorData a la CDA cuando se detectan valores fuera de rango.

How does your implementation work?El MqttClientConnector maneja suscripciones automáticamente en connectComplete(), con autenticación configurada en el archivo de propiedades.
La lógica del GDA analiza la humedad y envía comandos a la CDA según las condiciones definidas.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/carmenvt7/java-components/tree/labmodule10



### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- MqttConnectorTest
- 
- 

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- 
- 
- 

EOF.
