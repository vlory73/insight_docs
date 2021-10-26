---
description: >-
  This page will help you setting up the FX30 and prepare it to read data from a
  Modbus TCP device.
---

# FX30 setup

## Connect FX30 to PC

1. Turn on the FX30 and allow the LEDs to turn on.
2. Connect the microUSB cable to the FX30 and the computer.
3. Wait a few seconds until the network connection is established.
4. Open your browser and navigate to address [`http://192.168.2.2`](http://192.168.2.2).

## Configure the FX30

Configuring the FX30 is a straightforward and easy task, requiring only to define network settings (on Modbus TCP) and operator's APN configuration.&#x20;

![The web interface for the FX30 configuration](<../../../.gitbook/assets/image (17).png>)

### Configure network settings &#x20;

When using the FX30 Modbus TCP variant, it will be necessary to configure the network settings.\
This is necessary so that the FX30 is in the same network as the device that will be connected to Insight.

![](<../../../.gitbook/assets/image (13).png>)

{% hint style="info" %}
Save your changes.\
You will be prompted to switch OFF the FX30 and turn it ON again to restart with the new network settings. This is recommended to execute at this stage.
{% endhint %}

### Configure APN settings

The APN configuration is an important step without which no data sessions can be started.&#x20;

{% hint style="warning" %}
Check the APN settings with your operator before proceeding.&#x20;
{% endhint %}

In some instances, the FX30 may automatically detect the APN, based on the operator.

![](<../../../.gitbook/assets/image (16).png>)

{% hint style="info" %}
If the data session is already connected, skip the rest of this section.
{% endhint %}



Click on tab "SIM Configuration" and enter the APN settings.

![](<../../../.gitbook/assets/image (15).png>)

{% hint style="warning" %}
Don't forget to **Save** before leaving the page.

If you know the APN to be correct but cannot establish the connection, check the notes about network interfaces on [PC requirements](../../windows-pc-preparation.md) or contact your operator.
{% endhint %}

### Finishing up

{% hint style="info" %}
Hint: Keep the Insight FX30 Configuration page open in your browser as it will be handy during the next part.
{% endhint %}

{% hint style="success" %}
The FX30 is now configured. \
Proceed to [Part 2: Insight setup](../insight-setup/).
{% endhint %}
