# Restful-Booker-Performance-Testing

## This project focuses on performance testing of the Booking API endpoint of Restful-Booker,  Using Apache JMeter, I've simulated realistic user behavior to assess the system’s performance under various loads.

## Technology:
- apache-jmeter-5.6.3

## Prerequisite:
- install jdk 17
- install apache-jmeter
- setup Java_Home to the User variable
- setup Jmeter_Home to the User Variable

## how to run?
- ``` git clone ```
- ``` apache-jmeter.jar ```
- ``` open file : apache-jmeter-5.6.3\bin\booking.jmax ```
- ``` open with windows powershell ```
-  ``` ls ```
- ``` jmeter -n -t .\booking.jmx -l .\booking.jtl -e -o Reports ```

#### Caution : Before generating a new report for a different load test, you must delete the existing files and folders such as Report, jmeter.log, and booking.jtl. 
