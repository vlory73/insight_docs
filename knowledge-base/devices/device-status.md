# Device status

The devices listed on the settings page may have different statuses displayed depending on the timestamp of the last data received.

### Online

Any devices for which data has been received in the last 3 minutes are declared online. This evaluation serves both communication devices and measurement devices alike.

![A green status indicates that Insight has recently received data from the device.](<../../.gitbook/assets/image (66).png>)



### Warning

Both communication and measurement devices will display an orange state when the last data received is older than 3 minutes. 

![An orange status indicator means that no data has been received from it in the last 3 minutes.](<../../.gitbook/assets/image (64).png>)



The FX30 device will explicitly indicate an error of "No connection to the cloud" when the last payload receives is older than 3 minutes.

![The FX30 device show the message "No connection to cloud" as a complement to the orange status.](<../../.gitbook/assets/image (68).png>)



Additionally, the FX30 will also report if some of its Modbus servers or slaves are not communicating.

![The ](<../../.gitbook/assets/image (69).png>)



Finally, there is a third error message when the FX30 has not sent a heartbeat signal to its management service (AirVantage). This situation does not allow commands (configuration, geolocation and live mode) to be sent from Insight to the FX30.

![](<../../.gitbook/assets/image (67).png>)

{% hint style="info" %}
If the connectivity on-site is unaffected, a reboot command may help to reset the connection between the FX30 and AirVantage.
{% endhint %}



### Offline

When device payloads have not been received for more than 30 minutes, they are considered offline.

![The grey bar on the left side indicates that the device is deemed offline.](<../../.gitbook/assets/image (65).png>)

{% hint style="info" %}
Equipment in standby operation with very steady values do not send a lot of data and can be mistakenly be set as offline.

For these, it is recommended to have at least one tag (for a value that is expected to change) with a lower delta setting. 
{% endhint %}



