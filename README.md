# IPJCafe
# IPJ CAFE is a secure network for users to connect on cafe and use wifi for allocated time #
IPJCoffee has finalized a proposed Identity-based access and strong authentication system to protect the network from security threats and deliver a trusted network to customers.
We have implemented the secured network using Active-Directory and network Policy Service (NPS) on (remote authentication Dial-in user service) RADIUS server where you can load balance connection requests and forward them to the correct domain for authentication and authorization.

NPS perform centralized authentication and authorization and accounting for wireless, authenticating switched vpn services. We are using pfsense as a router and firewall software which helps us to configure wireless access point with radius, dhcp server and captive portal(modern interface for providing wifi connection). which used to configure the pfsense server as a gateway to authenticate user before entering into our network.

We are using 2 servers such as active directory and radius server to keep our sensitive information separate on the other server(domain controller) which store internal staff, devices and their IP addresses information in active directory. 

Pfsense server which is a powerful and flexible firewall and routing platform. We are using captive portal on that which is a software to forces users on an interface to authenticate before granting access to the internet.
![image](https://github.com/jocybersecurity23/IPJCafe/assets/141706333/d0800e30-a10a-4756-8437-16578bb08ee4)


IPJCOFFEE Network structure is a secured infrastructure. IPJCOFFEE Managers need to demonstrate the security practice demos for the employees like: “how long the password should be”, “password formats examples”, do not install unknown software which could affect the network.


Auditing System helps to add logs to the file for monitoring the network. Administrators need to collect and analysis the data for suspicious events. IPJCOFFEE Managers need to demonstrate the security practice demos for the employees like: “how they can contribute to secure IPJCOFFEE network”.
