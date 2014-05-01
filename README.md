jQuery-jDevice-Plugin
=====================

A jQuery plugin that helps you to detect mobile features.

Features
--------
* Helps you to Detect a mobile device trow jQuery

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
``` js
$(document).ready(function(){ if ($.device.isMobile()) { alert("is mobile"); } });
$(document).ready(function(){ if ($.device.isIPad()) {  alert("is an iPad"); } });
$(document).ready(function(){ if ($.device.isIPhone()) {  alert("is an iPhone"); } });
$(document).ready(function(){ if ($.device.isIPod()) {  alert("is an iPod"); });
$(document).ready(function(){ if ($.device.isIOSDevice()) {  alert("is an iOS device"); } });
$(document).ready(function(){ if ($.device.isAndroid()) {  alert("is an Android"); } });
$(document).ready(function(){ if ($.device.isBlackBerry()) {  alert("is a BlackBerry"); } });
$(document).ready(function(){ if ($.device.isWebOS()) {  alert("is a WebOS device"); } });
```

Contibution and Bug Report
--------
Please feel free if you want to contribute. 

Use the [GitHub issue tracker](https://github.com/creaworlds/jQuery-jDevice-Plugin/issues) for bug
reports and feature requests.