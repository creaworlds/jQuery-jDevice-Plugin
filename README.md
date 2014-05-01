jQuery-jDevice-Plugin
=====================

A jQuery plugin that helps you to detect mobile features.

Features
--------
* Helps you to Detect Mobile Device

Dependencies
--------

* jQuery 1.9 or higher

Usage
--------
``` js
function ConfigureDOM() {
	// Detects if current browser is insides of mobile device.
	if ($.device.isMobile()) {
		//TODO
	}
}
$(document).ready(ConfigureDOM);
``` 
 - **$.device** is the jDevice plugin and contains all methods descibed below:
 - **$.device.isIPad()** returns **true** if device is an **iPad**.
 - **$.device.isIPhone()** returns **true** if device is an **iPhone**.
 - **$.device.isIPod()** returns **true** if device is an **iPod**.
 - **$.device.isIOSDevice()** returns **true** if device is an **iOS Device**.
 - **$.device.isAndroid()** returns **true** if device is an **iOS Device**.
 - **$.device.isBlackBerry()** returns **true** if device is a **BlackBerry**.
 - **$.device.isWebOS()** returns **true** if device is a **WebOS** device.
 
Examples
--------
```
$(document).ready(function(){ if ($.device.isMobile()) { //TODO } });
$(document).ready(function(){ if ($.device.isIPad()) { //TODO } });
$(document).ready(function(){ if ($.device.isIPhone()) { //TODO } });
$(document).ready(function(){ if ($.device.isIPod()) { //TODO } });
$(document).ready(function(){ if ($.device.isIOSDevice()) { //TODO } });
$(document).ready(function(){ if ($.device.isAndroid()) { //TODO } });
$(document).ready(function(){ if ($.device.isBlackBerry()) { //TODO } });
$(document).ready(function(){ if ($.device.isWebOS()) { //TODO } });
```

Contibution and Bug Report
--------
Please feel free if you want to contribute. 

Use the [GitHub issue tracker](https://github.com/JimBobSquarePants/jQuery-Google-Analytics-Plugin/issues) for bug
reports and feature requests.