# Gateway Device Application (Connected Devices)

## Lab Module 08

Be sure to implement all the PIOT-GDA-* issues (requirements) listed.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? Se ha implementado un servidor CoAP que gestiona recursos para recibir datos de rendimiento del sistema y de sensores.
Esto permite la comunicación entre el GDA y los dispositivos que publican datos por CoAP.

How does your implementation work?El servidor se gestiona con CoapServerGateway, que añade handlers dinámicos para los recursos definidos.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/carmenvt7/java-components/tree/labmodule08


### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ConfigUtilTest
- SystemCpuUtilTaskTest
- SystemMemUtilTaskTest
- ActuatorDataTest
- SensorDataTest
- SystemPerformanceDataTest
- SystemStateDataTest
- DataUtilTest

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- CoapServerGatewayTest
- 
- 

EOF.
