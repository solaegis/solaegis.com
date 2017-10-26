+++
title = "SmartThings: SmartWeather Station Tile"
draft = false
date = "2017-06-18T14:00:00-04:00"
tags = ["SmartThings","Climate Control"]
image = "post/images/smartthings-logo.jpg"
menu = "main"

+++

Looking for an outdoor temperature device to use with [SmartThings][]?  Consider using [Wunderground][] instead.

It is easy to setup.  Follow these steps.

## Create device in SmartThings IDE
* Log into the [SmartThings IDE][]
* Select `My Devices`
* Select `+ New Device button` (Upper left side)
* Enter **Name**
* Fill in the **Device Network ID** with:
  * `Wunderground API`
* Select `SmartWeather Station Tile` from the **Type** pulldown
* **Version** should say `Published`
* **Hub** should be your SmartThings Hub
* Set **Group** as desired
* Select `Update`

## Configure newly created device
* Select the SmartWeather Station Tile device you just created
* In the **Preferences** section, select `[edit]`
* Fill in the zipcode field with your zipcode or Wunderground Weather Station ID:
  * **pws:**KCTBRANF10


## Finding your closest Wunderground Weather Station ID:
* Log into [Wunderground][]
* Select the search bar at the top and it will display `Find closest Station`
* Select `Find closest Station`
* Just under the Station Name, select `POYCC`
* The station name is in bold next to POYCC
* NOTE: Use the **pws:** prefix when putting it in the zipcode field in the above section

![alt text][SmartWeather Station Tile IOS]


[Wunderground]: https://www.wunderground.com

[SmartThings]: https://www.smartthings.com/
[SmartThings Logo]: https://www.solaegis.com/post/images/smartthings-logo.png
[SmartThings IDE]: https://graph.api.smartthings.com/
[SmartWeather Station Tile IOS]: https://www.solaegis.com/post/images/SmartWeather-Station-Tile-IOS.png
