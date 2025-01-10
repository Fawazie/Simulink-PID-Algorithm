# Simulink PID Algorithm
A simple Simulink model demonstrating PID control of a first-order system. The model calculates error from a setpoint, processes it through proportional, integral, and derivative components, and minimizes the error using feedback.

![image](https://github.com/user-attachments/assets/f38cb9ba-3f1c-4caa-b64c-dd5eeccd709a)


## How It's Made:

**Tech used:** Simulink.

The PID controller is built in Simulink using basic blocks. The error is calculated as the difference between the setpoint and system output. The error then feeds into the proportional integral and derivative branches, each scaled with adjustable gains. The output of the branches is then summed to generate the control signal, which drives the first-order system in a closed-loop system. 

The graph below illustrates how the system adjusts until it reaches its set point.

![image](https://github.com/user-attachments/assets/bdceac45-8e63-4b92-a7bb-2dde05eda564)





