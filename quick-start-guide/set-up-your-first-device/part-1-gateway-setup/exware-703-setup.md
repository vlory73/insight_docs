# eXware 703 setup

## Connect eXware 703 to PC

Connect an Ethernet network cable between the PC and ETH1 port on the eXware gateway&#x20;

{% hint style="warning" %}
You will have to set up your PC network interface to access IP address 192.168.0.1
{% endhint %}

&#x20;Access the page [https://192.168.0.1/machine\_config](https://192.168.0.1/machine\_config) with a browser to access the system settings of the eXware gateway.

* Username: admin
* Password: admin

{% hint style="danger" %}
Since the gateway will be permanently connected to the internet, it is critical to change the password.
{% endhint %}

## Configure the eXware 703



### Configure network settings

Navigate to the Network settings page





#### Default configuration

ETH0 / WAN: DHCP&#x20;

ETH1 / LAN: IP Address 192.168.0.1 Subnet mask: 255.255.255.0&#x20;



VNC service is also available and can be configured on the system settings page

