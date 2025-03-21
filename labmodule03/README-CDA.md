# Constrained Device Application (Connected Devices)

## Lab Module 03

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
simula el funcionamiento de distintos sensores y actuadores en un entorno IoT. Gestiona datos de sensores, actuadores y rendimiento del sistema a través de diferentes clases, permitiendo su correcta emulación y monitoreo.
How does your implementation work?
Cree clases para sensores de temperatura, humedad y presión, que heredan de BaseSensorSimTask, donde se define la lógica principal. Del mismo modo, los actuadores se gestionan mediante BaseActuatorSimTask. Los datos son administrados por DeviceDataManager, que se instancia en CDA. Además, se implementa JSONDataEncoder para garantizar el correcto funcionamiento de los unitests.
### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/carmenvt7/python-components/tree/labmodule03

### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ActuatorDataTest.py
- SensorDataTest.py
- SystemPerformanceDataTest.py
- HumiditySensorSimTaskTest.py
- PressureSensorSimTaskTest.py
- TemperatureSensorSimTaskTest.py
- HumidifierActuatorSimTaskTest.py
- HvacActuatorSimTaskTest.py

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- ConstrainedDeviceAppTest.py
- SensorAdapterManagerTest.py
- ActuatorAdapterManagerTest.py
- DeviceDataManagerNoCommsTest.py

EOF.
