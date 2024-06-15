# Project Title: API Performance Test using JMeter

## Project Summary: In this project, I did API performance Testing. Here I did Load Testing as well as Stress Testing.
### API: https://randomuser.me/api

### - Load testing is done to evaluate a system's performance under expected user loads and ensure it can handle peak traffic without issues.
### - Stress testing is done to determine a system's breaking point and behavior under extreme conditions beyond normal operational capacity.


## Prerequisites:
- JDK LTS Version
- ApacheJMeter

## How to run?
### Execute the following steps using JMeter:
- ``` git clone <repo_url> ```
- ``` Open ApacheJMeter ```
- ``` From ApacheJMeter open the JMX File ```
- ``` Finally Run ```

### Execute the following steps using CLI:
- ``` git clone <repo_url> ```
- ``` jmeter -n -t Performance_Testing.jmx -l Performance_Testing.csv ```

## Load and Stress Testing Excel Report:
- Drive Link: https://drive.google.com/drive/folders/1Ga3koEpZN8_PZoPeLyVYyQO5QThiCm7r?usp=sharing

## Output:
- The bottleneck point was identified at 12100 users when dealing in 20 mins(1200 sec).
- The highest Capacity Testing value was at 11800 users when dealing in 20 mins(1200 sec).

### Generated Report:
![Report](https://github.com/NaibDihan/API-Performance-Test/assets/80912556/4065d191-20a9-4480-ab2d-30ffa727f9c2)

### Excel Reports (Load and Stress Test)
![load test](https://github.com/NaibDihan/API-Performance-Test/assets/80912556/0179da56-e89c-49db-b1a0-34e43405112c)

![image](https://github.com/NaibDihan/API-Performance-Test/assets/80912556/461942e4-feb9-46eb-8903-2942414eba23)









