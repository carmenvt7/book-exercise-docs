# Constrained Device Application (Connected Devices)

## Lab Module 02

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
Mi implementacion aumenta SystemPerformanceManager para monitorear el uso de CPU y memoria, cree clases específicas para recopilar estas métricas, que luego se utilizan en handleTelemetry. También se añade registro en startManager y stopManager.
How does your implementation work?
Se crea la clase base BaseSystemUtilTask, de la cual heredan SystemCpuUtilTask y SystemMemUtilTask para recopilar métricas de CPU y memoria. Sus datos se obtienen mediante getTelemetryValue en handleTelemetry
### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/carmenvt7/python-components/tree/labmodule02

### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ConfigUtilTest
- SystemCpuUtilTaskTest
- SystemMemUtilTaskTest

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- SystemPerformanceManagerTest
- ConstrainedDeviceAppTest
- 

EOF.
