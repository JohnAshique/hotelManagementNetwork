# hotelManagementNetwork
In this project, a hotel network system has been implemented. Switches, routers, VLAN and SSH have been impleted.
In this project, a hotel network system has been implemented. There are 3 floors, where each floor is a different department. On the first level, there are Reception, store and Logistics. On the second floor there are Finance, HR and Sales/Marketing. Laslty, the third floor has IT and Admin.

There should be routers on each department/ floor.
All routers should be connected with serial DCE cable. Each floor should have switch and printer. Finally each department is expected to be in different VLAN.

The network between routers should be 10.10.10.0/30, 10.10.10.4/30, 10.10.10.8/30.


1st floor:
Reception - VLAN 80, Network of 192.168.8.0/24
Store- VLAN 70, Network of 192.168.7.0/24
Logisitics- VLAN 60, Network of 192.168.6.0/24

2nd floor:
Finance- VLAN 50, Network of 192.168.5.0/24
HRV - LAN 40, Network of 192.168.4.0/24
Sales - VLAN 30, Network of 192.168.3.0/24
