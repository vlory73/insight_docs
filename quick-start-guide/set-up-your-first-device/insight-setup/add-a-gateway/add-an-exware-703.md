# Add an eXware 703

Upon pressing again on the button to **Add new device**, we will now head to the **New devices** tab and from there select **eX703**.

![](<../../../../.gitbook/assets/image (48).png>)

Once on the eXware device page, fill in the **Device detail** section and give the device a recognizable, and preferably unique name. \
You can give it the same name as the Equipment or a variation of it, for example.

A version is mandatory, but this is not a critical field. Just set it to **1**, for now.

![](<../../../../.gitbook/assets/image (97).png>)

In the **Data Acquisition Unit Configuration** section, introduce the **Serial Number** of the eXware 703.

![](<../../../../.gitbook/assets/image (65).png>)

\
This can be found in the **System Settings / System** page, the eXware kit box and the label on the device.

{% hint style="info" %}
Pro Tip: If you kept the System Settings page open on your browser, simply copy and paste the **Serial Number** from one page to the other.
{% endhint %}

Leave the **Key Frame Interval** and **Device Status Notifications** setting with their default settings, for now.

Press **Save and Send Configuration** and we will finish the setup in the next section.

## Download configuration manually

In order to have the eXware ready for over-the-air (OTA) configuration, it is necessary to execute an initial, manual retrieval of the configuration.

Ensure that the device is connected to the internet and that ports 80, 443 and 8883 are enabled by your firewall settings.

{% hint style="warning" %}
Advanced: SSH into the device and use **ping 8.8.8.8** or **ping google.com** to check for an internet connection.
{% endhint %}



Access the IP address of the gateway on a web browser and log in.

&#x20;![](<../../../../.gitbook/assets/image (84).png>)

{% hint style="info" %}
This password is not affected by the System Settings password.

* Username: admin
* Password: admin
{% endhint %}

Type anything into the field and **Save** the change

![](<../../../../.gitbook/assets/image (99).png>)



If the configuration is retrieved successfully, the gateway will restart the application to take in the new configuration.

{% hint style="info" %}
After this operation, the **Save and Send Configuration** button will push the new configuration directly to the device.
{% endhint %}
