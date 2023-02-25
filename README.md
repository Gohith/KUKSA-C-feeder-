# KUKSA-CPP-feeder
A feeder software which feeds the vehicle signal data to KUKSA server 
in detail- this software sends the vehicle signal data which was embed with VSS(Vehicle Signal Specification) to KUKSA server either in gRPC or WS. More details of KUKSA Vehicle Abstraction Layer server and VSS can be found in following links.

https://github.com/eclipse/kuksa.val --- KUKSA VAL Server

https://covesa.github.io/vehicle_signal_specification/ --- VSS by COVESA

Briefly the application architecture looks like:

![image](https://user-images.githubusercontent.com/23610194/221366021-43910fef-dee2-4b18-98f0-ecf2ca3c39cb.png)



This C++ application requires some libraries (mentioned below) for connectivity to server and also parsing signal nodes from VSS and retrieving CAN messages from .dbc files. The whole application requires CMake to generate build system. 
