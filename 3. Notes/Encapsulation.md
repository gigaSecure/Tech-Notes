[[MOC Networking]]

# Encapsulation
Created:  [[2022-07-01]]
Tags: #fleeting 

---
Abstract:
- Encapsulation
- De-encapsulation
- Why Encapsulation and De-encapsulation are important

---
Encapsulation, is the process by which data can be sent from one computer to another. 


![[image.jpeg]]
### Encapsulation happens when sending a message
The current layer will be covered with the headers of the next layer and repeats the process till Layer 1. 


### De-encapsulation happens when receiving a message
When the message is received by the second computer, it reverses the process -- starting at the physical layer and working up until it reaches the application layer, stripping off the added information as it goes. This is referred to as _de-encapsulation_. 



It happens when receiving a message.  At each layer, a header is added during encapsulation, and removed during de-encapsulation.



Computers all follow the same process of encapsulation to send data and de-encapsulation upon receiving it. The processes of encapsulation and de-encapsulation are very important -- not least because of their practical use, but also because they give us a standardised method for sending data. This means that all transmissions will consistently follow the same methodology, allowing any network enabled device to send a request to any other reachable device and be sure that it will be understood -- regardless of whether they are from the same manufacturer; use the same operating system; or any other factors.






### References
1. https://tryhackme.com/room/introtonetworking