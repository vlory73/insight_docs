# Add the FX30

Upon pressing again on the button to **Add new device**, we will now head to the **New devices** tab and from there select **FX30**.

![](../../../.gitbook/assets/image%20%2848%29.png)

Once in the FX30 device page, fill in the **Device detail** section give it a recognizable name.   
You can give it the same name as the Equipment or a variation of it, for example.

A version is mandatory, but this is not a critical field. Just set it to **1**, for now.

![](../../../.gitbook/assets/image%20%2835%29.png)

In the **Data Acquisition Unit Configuration** section, we are going to select the type of **FX30**.  
The FX30S is used for Modbus RTU \(RS-485\).  
Introduce the **IMEI** and **Serial Number** of the FX30.  
These can be found in the DAU Configuration page, the DAU box and the label on the device.

{% hint style="info" %}
Pro Tip: If you kept DAU Configuration page open in your browser, simply copy and paste the **IMEI** and **Serial Number** from one page to the other.
{% endhint %}

Since we want to use the GNSS facilities of the FX30 to keep track of our Equipment, we will enable geo-location. When enabling the geo-location, a time interval for location reporting must be set.  
The interval is set in minutes by means of a dropdown and an interval of zero \(0\) defines that the location is sent only one time, just after the FX30 powers up.

![](../../../.gitbook/assets/image%20%2845%29.png)

{% hint style="danger" %}
Both IMEI and Serial Number must be correctly introduced or the system will not work.  
Please note that only the IMEI has a validation algorithm for the input provided.
{% endhint %}

Press **Save and Send Configuration** and we will finish the set up in the next page.

