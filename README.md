
# Project Name

IP-Address-Fynder


## Summary

A Java project IP-Address-Fynder is designed to retrieve and display th IP Address associated with the machine it's running on.
## Core Functionality

The primary function is to obtain and present the IP address.

* Localhost/Loopback Address : Retrieving the loopback address(typically 127.0.0.1 for IPv4 or ::1 for IPv6).

* Network Interface Addresses : Identifying and retrieving the IP address assigned to the network interfaces of the machine.


## Implementation Details

* java.net Package :- Project will utilize classes from the java.net package, such as  InetAddress.

* InetAddress :- This class represent an Internet Protoco (IP) address.

Methods :

1.getByName() - It returns the instance of InetAddress containing LocalHost IP & name.

2.getHostName() - It returns the hostname of IP address.

3.getHostAddress() - It returns the IP address in string format.

4.getLocalHost() - It returns the instance of InetAddress containing Hostname IP & address.


## Screenshots

![Image](https://github.com/user-attachments/assets/11ecd963-b320-4208-b071-40178d9d1684)

![Image](https://github.com/user-attachments/assets/fc648a3b-71f1-44ea-a612-f0a141ab7320)

![Image](https://github.com/user-attachments/assets/e20b3789-d164-44a3-9f6d-e84777754de7)
