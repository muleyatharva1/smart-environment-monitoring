# smart-environment-monitoring

## **Overview**
The Smart Environmental Monitoring System is developed to measure and report key environmental parameters, including air quality, temperature, humidity, and light intensity. It leverages the STM32F401RE microcontroller alongside various sensors to deliver real-time data. Built using HAL libraries and STM Cube MX, the system ensures ease of use and cost-effectiveness with its affordable components.

## **Hardware description**
* STM32F401RE: The main microcontroller that handles data acquisition and processing.
* MQ135: Air quality sensor for detecting various gases.
* DHT11: Sensor for measuring temperature and humidity.
* LDR: Light-dependent resistor for measuring light intensity.
* LCD Display (Additional): For displaying sensor readings. (Is implemented in current version)

## **Software Used**
* STM32CubeMX: For initializing the STM32F401RE peripherals.
* HAL Libraries: For hardware abstraction and easier coding.

## **Features**
* Measures and reports air quality, temperature, humidity, and light intensity.
* Uses cost effective and easy-to-build methods.
* Code is centralized in a single main.c file for simplicity, though this might affect performance

## **Setup Instructions**
1. Hardware configuration
   - Connect the MQ135 sensor to the STM32F401RE.
   - Connect the DHT11 sensor to the STM32F401RE.
   - Connect the LDR to the STM32F401RE.
   - Connect an LCD display to the STM32F401RE.
2. Software configuration
   - Open STM32CubeMX and configure the peripherals.
   - Generate the initialization code using STM32CubeMX.
   - Import the generated code into your IDE.
   - Implement sensor reading and data processing in the main.c file.

## **Usage**
* upload the code to your STM32F401RE.
* Open the Serial Monitor to view the sensor readings.
* Use the sensor data for your specific applications.

## **Acknowledgements**
* Thanks to the creators of STM32CubeMX and HAL libraries for providing the tools needed to simplify development
   
   
   
