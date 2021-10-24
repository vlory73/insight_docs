# Add an eXware 703

Upon pressing again on the button to **Add new device**, we will now head to the **New devices** tab and from there select **eX703**.

![](<../../../../.gitbook/assets/image (68).png>)

~~Once on the FX30 device page, fill in the **Device detail** section and give the device a recognizable name. ~~\
~~You can give it the same name as the Equipment or a variation of it, for example.~~

~~A version is mandatory, but this is not a critical field. Just set it to **1**, for now.~~

![](<../../../../.gitbook/assets/image (32).png>)

~~In the **Data Acquisition Unit Configuration** section, we are going to select the type of **FX30**.~~\
~~The FX30S is used for Modbus RTU (RS-485).~~\
~~Introduce the **IMEI** and **Serial Number** of the FX30.~~\
~~These can be found in the Insight FX30 Configuration page, the FX30 kit box and the label on the device.~~

{% hint style="info" %}
~~Pro Tip: If you kept Insight FX30 Configuration page open on your browser, simply copy and paste the **IMEI** and **Serial Number** from one page to the other.~~
{% endhint %}



{% hint style="danger" %}
~~Both IMEI and Serial Number must be correctly introduced or the system will not work.~~\
~~Please note that only the IMEI has a validation algorithm for the input provided.~~
{% endhint %}

Press **Save and Send Configuration **and we will finish the setup in the next section.

## Download configuration manually

In order to have the eXware ready for over-the-air (OTA) configuration, it is necessary to execute an initial, manual retrieval of the configuration.

Ensure that the device is connected to the internet.

{% hint style="warning" %}
Advanced: SSH into the device and use **ping 8.8.8.8** or **ping google.com** to check for internet connection
{% endhint %}

Access the IP address of the device on a web browser.

Type anything into the field

Submit the change

If the configuration is retrieved successfully, the device will restart.





{% hint style="info" %}
After this operation, the **Save and Send Configuration** button will push the new configuration directly to the device.
{% endhint %}













