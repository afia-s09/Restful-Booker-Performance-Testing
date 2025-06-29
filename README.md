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

#### Caution : Before generating a new report for a different load test, you must delete the existing files and folders such as Reports, jmeter.log, and booking.jtl

## HTML Report :
![Step-1](https://github.com/user-attachments/assets/4f9bde67-a6a1-4367-bf0d-dd71ea06e91d)
![Step-2](https://github.com/user-attachments/assets/1ea6caf7-550b-449e-9bcb-c3f0bbc8f1b7)
![Step-3](https://github.com/user-attachments/assets/f4e3aa23-4b38-4b70-a983-6b1a7ed52fc9)
![Step-4](https://github.com/user-attachments/assets/f91e5762-e062-42f1-b92c-7fe36646a84a)
![Step-5](https://github.com/user-attachments/assets/b47c3d34-d9a5-43c3-9bbe-a316ae4f0ce9)
![Step-6](https://github.com/user-attachments/assets/e8cbcc4b-9240-4a59-bfdc-b2ce9a7a8991)

## Load Test Report:
![image](https://github.com/user-attachments/assets/dc8e70e1-070c-4c7d-85b6-c59f8681868e)

## Stress Test Report:
![image](https://github.com/user-attachments/assets/e0586e0d-e90c-4f99-a6fe-e21114bf0995)

#### Report Description: The server performs reliably up to 833 users with zero errors. As user load increases to 1666 and beyond, the error rate gradually rises while throughput remains capped around 2.68 req/sec. The system reaches its stress limit between 1700–1800 users, where performance degrades and errors increase significantly.







