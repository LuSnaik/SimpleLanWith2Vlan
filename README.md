# SimpleLanWith2Vlan
A Simple LAN with two VLAN one for HR Dept. and other for I.T. Dept.

PS:  there is tag  that I wrote in portuguese when I was creating this lab.



Tags: RH - HR, 

Dept. T.I. - I.T. Dept.

Andar - Floor.

On this simple lab there is two vlan configured for HR and I.T. Dept.

The two vlan do note communicate because we are using a L2 switch and there is no router to do the routing. But the intention was to create a LAN with two VLAN with a DHCP server and to locate them on different floor and connect those floors with using switch.

All the devices on HR vlan communicate with each other.

And on the I.T. Dept. vlan all the devices communicate with each other.

Devices on diferentes vlan do not communicate.

On PDU list window we can see that, where PC7 from HR vlan communicate with laptop0 from HR vlan. And the I.T printer communicate with laptop0 from I.T. Dept.

When two devices from different vlans tried to communicate it failed.
