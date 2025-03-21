# Gateway Device Application (Connected Devices)

## Lab Module 02

Be sure to implement all the PIOT-GDA-* issues.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
monitorear el uso de recursos del sistema, como CPU y memoria, a través de la clase SystemPerformanceManager, que ahora puede gestionar estos datos correctamente.
How does your implementation work?
Se definen métodos en SystemPerformanceManager que invocan SystemCpuUtilTask y SystemMemUtilTask para recopilar métricas. Estas clases heredan de BaseSystemUtilTask, donde se establecen getters y setters. Además, se sobrescribe el método getTelemetryValue y se realizan ajustes en el Logger para evitar errores en las pruebas.
### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/carmenvt7/java-components/tree/labmodule02


### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ConfigUtilTest
- SystemCpuUtilTest
- SystemMemUtilTaskTest

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- GatewayDeviceAppTest
- SystemPerformaneceManagerTest
- 

EOF.
