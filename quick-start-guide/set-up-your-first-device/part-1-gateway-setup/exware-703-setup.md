# eXware 703 setup

## Network setup

Connect an Ethernet network cable between the PC and ETH1 port on the eXware gateway&#x20;

{% hint style="warning" %}
You will have to set up your PC network interface to access IP address 192.168.0.1
{% endhint %}

&#x20;Access the page [https://192.168.0.1/machine\_config](https://192.168.0.1/machine\_config) to access the system settings of the eXware gateway.





ETH0 / WAN: DHCP&#x20;

ETH1 / LAN: IP Address 192.168.0.1 Subnet mask: 255.255.255.0 Settings:&#x20;

&#x20;Username: admin Password: admin



## Download configuration manually

In order to have the eXware prepared for configuration over-the-air (OTA), it is necessary to execute an initial, manual retrieval of the configuration.

This is done by accessing the IP address of the device on a web browser.

{% hint style="info" %}
VNC service is also available and can be configured on the system settings page
{% endhint %}

