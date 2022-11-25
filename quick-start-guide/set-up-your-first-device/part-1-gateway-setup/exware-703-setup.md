# eXware 703 setup

## Connect the eXware 703 to PC

Connect an Ethernet network cable between the PC and ETH1 port on the eXware gateway&#x20;

{% hint style="info" %}
You will have to set up your PC network interface to access IP address 192.168.0.1
{% endhint %}

&#x20;Access the page [https://192.168.0.1/machine\_config](https://192.168.0.1/machine\_config) with a browser to access the system settings of the eXware gateway.

{% hint style="warning" %}
You will be greeted by a warning that the connection is not private.

This is because certificates are not present to guarantee an HTTPS connection.

It is safe to proceed despite the warnings from the browser.
{% endhint %}

Click on the **Advanced** button to expand and follow the link provided.

![You can safely proceed to the address by clicking the link.](<../../../.gitbook/assets/image (71) (1).png>)

Enter the user name and password.

![](<../../../.gitbook/assets/image (74).png>)

{% hint style="info" %}
#### Default user settings

* Username: admin
* Password: admin
{% endhint %}

{% hint style="danger" %}
Since the gateway will be permanently connected to the internet, it is very important to [change the password](exware-703-setup.md#change-password).
{% endhint %}

## Configure the eXware 703

Upon entering the System Settings page, the landing page allows changing the language.

![](<../../../.gitbook/assets/image (67).png>)

{% hint style="danger" %}
Use language change with care, in particular, if you are not fluent in the selected language.
{% endhint %}

### Configure network settings

Navigate to the **Network** page and press the **Edit** button to change the network interfaces configuration.

{% hint style="info" %}
#### Default network configuration

ETH0 / WAN: DHCP&#x20;

ETH1 / LAN: IP Address 192.168.0.1 Subnet mask: 255.255.255.0&#x20;
{% endhint %}

{% hint style="danger" %}
After changing the network configuration, you will need to use the new IP address to access the System Settings page again.

You may also need to change the PC's network settings.
{% endhint %}

### Enabling/disabling services on the eXware 703

During commissioning, it may be useful to enable some of the services that eXware provides.

For example, the SSH service can be used for troubleshooting and VNC can be used as an alternative to the web browser.

Navigate to the **Services** page.

![](<../../../.gitbook/assets/image (64) (1).png>)

To enable or disable services, follow the steps:

* Select the service

![](<../../../.gitbook/assets/image (68).png>)

* Press **Edit** on the top-right corner

![](<../../../.gitbook/assets/image (73) (1).png>)

* Change the settings, including the **Enabled** switch

![](<../../../.gitbook/assets/image (69) (1).png>)

* Finish by saving&#x20;

![](<../../../.gitbook/assets/image (70).png>)

{% hint style="warning" %}
Once the gateway is ready for deployment, it is highly recommended to disable the SSH and VNC services.
{% endhint %}

### Change password

![](../../../.gitbook/assets/SeekPng.com\_construction-png\_231683.png)

### Finishing up

{% hint style="info" %}
Hint: Navigate to **System** and keep this page open in your browser as it will be handy during the next part.
{% endhint %}

{% hint style="success" %}
The eXware 703 is now configured. \
Proceed to [Part 2: Insight setup](../insight-setup/).
{% endhint %}

