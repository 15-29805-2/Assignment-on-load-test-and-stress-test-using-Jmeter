# Performance Testing (Load Testing) with JMeter - Restful-Booker API

## Project summary
This project focuses on performance testing of the public Restful-Booker API using Apache JMeter. The goal is to simulate real-world user behavior and analyze how the system performs under load and stress.

## Technology used
- Apache JMeter 5.6.3
- Java
- Restful Booker API: [https://restful-booker.herokuapp.com]

## Prerequisites
- Download and install [JMeter](https://jmeter.apache.org/download_jmeter.cgi)
- Java installed and added to system path
- Internet access (to connect with public API)
  
## How to run
- ```git clone```
- ```open Jmeter```
- ```Load Booking.jmx```
- ```open with terminal and command "jmeter -n -t .\Booking.jmx -l .\Booking.jtl -e -o Reports"```

##### Caution
- To regenerate reports, delete the Report/ folder and .jtl file before re-running.
- All test requests include Accept: */* and Content-Type: application/json
- Gaussian Random Timer: Deviation = 2000ms, Constant Delay = 500ms

# Reports screenshot

![image](https://github.com/user-attachments/assets/d122468d-7d17-469a-8efa-668c023f94ba)

![image](https://github.com/user-attachments/assets/7e98164b-4f25-452e-a7d5-d6a938617494)

# Load Test Report screenshot
![Load 400 sec](https://github.com/user-attachments/assets/96430ac8-3647-479f-bc01-6bab3b1eeafc)

![Load 400 stat](https://github.com/user-attachments/assets/64ea5fa7-dc55-4cb2-b4d8-cb7f8a2d94bc)

![load 400 error](https://github.com/user-attachments/assets/97299534-9c6c-4974-b080-1e378aa5d779)

# Stress test Report screenshot
![stress 2 2 3](https://github.com/user-attachments/assets/353c1c9e-d329-410d-81cb-536e677591e4)

![stress 2 2 3 stat](https://github.com/user-attachments/assets/c8657e49-de17-472b-a768-a3d7e76c9ede)

![stress 2 2 3 err](https://github.com/user-attachments/assets/e2510b59-202a-4e73-9881-ad3b83957dcb)









