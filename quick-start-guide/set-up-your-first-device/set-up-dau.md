---
description: >-
  This page will help you setting up the DAU and prepare it to read data from a
  Modbus TCP device.
---

# Part 1: DAU setup

## Connect DAU to PC

1. Turn on the DAU.
2. Connect the micro-USB cable to the DAU and the computer.
3. Wait a few seconds until the network connection is established.
4. Open your browser and navigate to address `http://192.168.2.2`.

![After connection is established, the result should look similar to this.](../../.gitbook/assets/image%20%281%29.png)

## Configure the DAU

lorem ipsum dolor...

### Configure network settings

When using the Ethernet variant of the DAU, it will be necessary to configure the network settings.  
This is necessary so that the DAU is in the same network as the device that will be monitored on Insight.

![](../../.gitbook/assets/dau_config_ethernet.png)

{% hint style="success" %}
Switch the DAU OFF and ON again to restart with the new network settings.
{% endhint %}

### Configure APN settings

![](../../.gitbook/assets/image%20%283%29.png)

{% hint style="info" %}
If the data session is already connected, skip this step.
{% endhint %}

The APN configuration is an important step without which no data sessions with the operator will be started.

In some occasions, the SIM card may configure the APN automatically.

{% hint style="warning" %}
Check the APN settings with your operator before proceeding.
{% endhint %}

Click on tab "SIM Configuration" and enter the APN settings.

![](../../.gitbook/assets/dau_config_provider.png)



