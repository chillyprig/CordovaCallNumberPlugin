CordovaCallNumberPlugin
=======================

Call a number directly from your cordova application.

Chillyprig - Fork to add (Android) make the app become active after phone calls.

Install the plugin using:

``` java
cordova plugin add https://github.com/Rohfosho/CordovaCallNumberPlugin.git
```

Use the plugin in your JS file:
``` javascript
window.plugins.CallNumber.callNumber(onSuccess, onError, number);
```

Make sure to create onSuccess and onError call back functions.
