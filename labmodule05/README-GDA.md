# Gateway Device Application (Connected Devices)

## Lab Module 05

Be sure to implement all the PIOT-GDA-* issues (requirements) listed.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
mejora la comunicación entre sensores y actuadores para garantizar la interacción entre CDA y GDA

How does your implementation work?
Implementé métodos en SensorData, ActuatorData, SystemPerformanceData y SystemStateData, incluyendo getters, setters y handleUpdateData. SystemPerformanceManager ahora recopila métricas de CPU, memoria y disco
También hice que DataUtil permita convertir estos datos a JSON con Gson, facilitando la comunicación con CDA.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/carmenvt7/java-components/tree/labmodule05


### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ActuatorDataTest
- SensorDataTest
- SystemPerformanceDataTest
- SystemStateDataTest
- DataUtilTest.java

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- SystemPerformanceManagerTest
- DataIntegrationTest
- DeviceDataManagerNoCommsTest
- GatewayDeviceAppTest
- 

EOF.
