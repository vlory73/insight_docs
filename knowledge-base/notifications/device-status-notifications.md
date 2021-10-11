# Device status notifications

Status notifications give the opportunity to configure SMS and email messages to the different device statuses.



### Where to find and configure the status notifications

Navigate to **Settings / Devices** and choose a communication device (e.g. FX30).

Within the device's settings, there is a section to configure its status notifications.

![The FX30 has three different device statuses available for notifications](<../../.gitbook/assets/image (65) (1).png>)

{% hint style="info" %}
 Device status notifications are set for the communication device as well as for all the Modbus devices connected to it.
{% endhint %}



Each status has a set and a reset state that can be selected independently to send messages and their content for SMS and email contexts.

Their meaning is reflected in the table below.

| STATUS                            |                                 SET                                |                             RESET                             |
| --------------------------------- | :----------------------------------------------------------------: | :-----------------------------------------------------------: |
| Online                            |                        The device is online                        |                     The device is offline                     |
| Communication to Insight          |                The device is sending data to Insight               |      The device has not sent data in the last 30 minutes      |
| Communication to gateway services | The heartbeat is being received and gateway services are available | The device has lost communication with its management service |



### Setting up the notification messages

The notifications are configured in a very similar way as the standard notifications on Modbus devices, with the possibility to configure the independent messages for SMS and email.

![The trigger detais section is where messages are defined](<../../.gitbook/assets/image (69) (1).png>)

{% hint style="warning" %}
At this moment, the trigger timer has no effect on the device status notifications.
{% endhint %}

### Setting up recipients

Click on "Attach User" to open a selection window for all users.

After adding a user, the icons on the right side allow the choice of the notification type.

![Miki Starfall will receive SMS notifications for all the device status messages.](<../../.gitbook/assets/image (70) (1).png>)



### Finishing up

To finalise the configuration, click on "Save and Send configuration" at the bottom of the page.
