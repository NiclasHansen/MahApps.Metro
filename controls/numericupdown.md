---
layout: no-sidebar
title: NumericUpDown - MahApps.Metro
---

The NumericUpDown control is used to increase or decrease a numeric value.


![]({{site.baseurl}}/images/numeric_up_down.png)

If you press the  `+` button the value of the NumericUpDown control increases by the value set in `Interval`. Pressing `-` decreases the value.
If you press and hold `+` or `-` then value keeps increasing, decreasing respectively.

##SpeedUp

If you press and hold `+` or `-` for some longe time then the `Value` increases or decreases much faster. If this behaviour is not desired you can turn this off by setting `Speedup=false`. By default this behaviour is enabled.

##InterceptArrowKeys

You can also increase or decrease the `Value` using `Arrow Up` or `Arrow Down`. You can enable this behaviour if you set `InterceptArrowKeys=true`. By default this behaviour is enabled.

By specifying a value for `Minimum` or `Maximum` you can set the range for legal values.

##StringFormat
You can also set the `StringFormat` to format the number of the Value that is displayed in the control.

e.g.

* C2
* N4
* E1

##Example

Following line will provide a NumericUpDown that allows numers from 0 to 1000. Furthermore by pressing `+` the value gets increased by 5. The value will be shown as currency with two decimal places:
`<Controls:NumericUpDown Minimum = 0, Maximum = 10000, Interval = 5, StringFormat="C2"/>`
