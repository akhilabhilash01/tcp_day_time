#Concurrent TCP/IP Day Time Server - Client in C
**SAMPLE OUTPUT:**
-----------------
***Server side:***
> gcc filename.c -o filename 

> ./filename 3000
```
Port: 3000
[+]Bind
[+]Listening for the client
Client 1 requested for time at Fri Oct  8 05:25:54 2021
```
***Client side:***
> nc 127.0.0.1 3000
```
Fri Oct  8 05:25:54 2021
```
![image](https://user-images.githubusercontent.com/91663578/136503217-e76a7aef-95ca-4fd2-873d-e8bbd1c3efd4.png)

<!--P.S. Software used: CoCalc Online Linux Terminal -->  
