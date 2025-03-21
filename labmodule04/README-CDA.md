# Constrained Device Application (Connected Devices)

## Lab Module 04

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
conecta el SenseHAT Emulator con los datos de sensores y actuadores, permitiendo observar cómo reacciona el dispositivo a cambios en temperatura, presión y humedad.
How does your implementation work?
los sensores de temperatura, presión y humedad heredan de BaseSensorSimTask y almacenan datos en SensorData. Los actuadores, como HumidifierEmulatorTask, HvacEmulatorTask y LedDisplayEmulatorTask, derivan de BaseActuatorSimTask y muestran activaciones en la pantalla LED del emulador. SensorAdapterManager permite cargar dinámicamente los emuladores o, si no están activos, usa _initEnvironmentalSensorTasks. Además, se han comentado líneas de código relacionadas con la pantalla para evitar errores con BufferFrame, ya que solo funcionarían en un dispositivo real.
### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: https://github.com/carmenvt7/python-components/tree/labmodule04


### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- SenseHatEmulatorQuickTest.py
- HumidifierActuatorSimTaskTest
- HvacActuatorSimTaskTest
- 

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- HumidityEmulatorTaskTest.py
- PressureEmulatorTaskTest.py
- TemperatureEmulatorTaskTest.py
- HumidifierEmulatorTaskTest.py
- HvacEmulatorTaskTest.py
- LedDisplayEmulatorTaskTest.py
- SensorEmulatorManagerTest
- ActuatorEmulatorManagerTes
- SensorAdapterManagerTest
- ActuatorAdapterManagerTest
- DeviceDataManagerNoCommsTest
- ConstrainedDeviceAppTest
  

EOF.
