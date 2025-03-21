# Constrained Device Application (Connected Devices)

## Lab Module 05

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
mejora la comunicación entre sensores y actuadores para garantizar la interacción entre CDA y GDA.

How does your implementation work?
Se actualiza SystemPerformanceManager para gestionar mejor la telemetría y la escucha de datos, permitiéndole procesar SystemPerformanceData y SystemPerformanceMessage. Además, se crean métodos en DataUtil para convertir ActuatorData, SensorData y SystemPerformanceData a formato JSON y viceversa. El JsonDataEncoder ya estaba configurado desde labmodule03 para garantizar la compatibilidad con los tests unitarios.
### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/carmenvt7/python-components/tree/labmodule05


### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- DataUtilTest
- 
- 

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- SystemPerformanceManagerTest
- DataIntegrationTest
- 

EOF.
