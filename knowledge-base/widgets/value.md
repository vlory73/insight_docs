---
description: This page describes the Value widget and its settings.
---

# Value

## Widget visualization

The Value widget is one of the simplest forms of visualization of data and also one of the easiest to understand. The widget is composed of a text area on the header, a numeric representation of the data in the middle, and the unit selected on the tag configuration at the bottom of the widget.

![Value widget](<../../.gitbook/assets/image (76).png>)

## Widget configuration

![Adding a Value widget to the dashboard](<../../.gitbook/assets/image (9).png>)

Some of the functions and the differences of behavior in different dashboard types are common to other widgets.&#x20;

### Widget settings for Equipment

![Available settings for the Value widget on Equipment dashboards](<../../.gitbook/assets/image (34).png>)

| FIELD NAME     | FUNCTION                                                                                                                                                                                                 |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HEADER NAME    | The text displayed on the top of the widget.                                                                                                                                                             |
| DEVICE         | <p>The device or devices from which the data is coming from.</p><p>Select as many devices as required.<br>Selecting "All devices" will automatically include any new devices added to the Equipment.</p> |
| SELECT ONE TAG | <p>The data point that is going to be displayed.<br> If multiple devices are selected, only tags with the same name will be valid choices.</p>                                                           |
| TIME PERIOD    | Represents the time period and calculation method for the tag.                                                                                                                                           |



The TIME PERIOD settings can be interpreted as per the table below.

| TIME PERIOD          | FUNCTION                                                                        |
| -------------------- | ------------------------------------------------------------------------------- |
| Current Total        | The sum of all the last received values for the tag of one or multiple devices. |
| Current Average      | The average of the last received values for the tag of one or multiple devices. |
| 24 hours - Average   | The 24 hour average of the values received for one or multiple devices.         |
| This week - Average  | The current week's average of the values received for one or multiple devices.  |
| This month - Average | The current month's average of the values received for one or multiple devices. |
| All time - Average   | All time average of all the values received for the devices.                    |

{% hint style="warning" %}
If the units have tags with the same name but the units in the tag configuration are different, the unit text will be presented as "**#**".
{% endhint %}

### Widget settings for Group

![The Value widget settings for Group are very similar to those in Equipment dashboards](<../../.gitbook/assets/image (70).png>)

The settings for Group now include a selection of the Equipment that belongs to the Group.\
This selection allows to get totals and averages from all units or a sub-set of units of the Group.\
Similarly to the Device selection in Equipment dashboard, selecting All Equipment in this setting will ensure that any future units added to the Group are included automatically.

All the remaining behavior and settings are as in the Equipment dashboard.

![Equipment selection for a Value widget on a Group dashboard ](<../../.gitbook/assets/image (31).png>)

![Future equipment will not be taken into account in the widget calculations](<../../.gitbook/assets/image (90).png>)

![Any equipment added at later stage will be taken into account in the widget calculations](<../../.gitbook/assets/image (63).png>)

### Widget settings for Home dashboard

![The Home dashboard offers the ultimate flexibility.](<../../.gitbook/assets/image (13).png>)

| VIEW TYPE   | CHOICES                                                                                                                                                                          |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| All Devices | Select any device or all devices.                                                                                                                                                |
| Group       | <p>Select any group or all groups.</p><p>Select any equipment or all equipment from the selected groups.</p><p>Select any device or all devices from the selected equipment.</p> |
| Equipment   | <p>Select any equipment or all equipment.</p><p>Select any device or all devices from the selected equipment.</p>                                                                |

Similarly to the Device selection in Equipment dashboard and Equipment selection in Group dashboards, selecting All Devices, All Equipment or All Groups will ensure that any future elements are included automatically.

{% hint style="info" %}
Users designing the dashboard will only be able to include Equipment and Groups to which they have access to.
{% endhint %}
