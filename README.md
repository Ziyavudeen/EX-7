# EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND

# DATE : 20.04.2023


# AIM :
#### To write the python program for simulating Traceroute command

# ALGORITHM :

#### 1. Start the program.
#### 2.Get the frame size from the user.
#### 3.To create the frame based on the user request.
#### 4.To send frames to server from the client side.
#### 5.If your frames reach the server, it will send ACK signal to client otherwise it will sendNACK signal to client.
#### 6.Stop the program



# PROGRAM :
```PY
## Developed : Ziyavudeen A
## Reg no : 212221040189
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```
# OUTPUT :

![output_7](https://github.com/Javith-farkhan/EX-7/assets/94296805/2f4211ba-d357-4824-a62a-0c6189255216)



# RESULT:
#### Thus, the python program for simulating Traceroute command was successfully executed.

