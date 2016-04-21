# Android device year module [![gitTio](http://gitt.io/badge.svg)](http://gitt.io/component/com.ti.androiddeviceyear)

###Rationale

Sometimes its necessary on Android to degrade performance for low end devices. This module exposes: https://github.com/facebook/device-year-class for Appcelerator Titanium

###Methods/Functions

initialize, returns a boolean, a false indicates something has fallen over, i am catching java.lang.Throwable just in case something bad happens

```
require("com.ti.androiddeviceyear").getDeviceYear();
```

I found devices < 2012 to be worth degrading performance for.

### Get it

Download the latest distribution ZIP-file and consult the [Titanium Documentation](http://docs.appcelerator.com/titanium/latest/#!/guide/Using_a_Module) on how install it

Or simply use the [gitTio CLI](http://gitt.io/cli) [![gitTio](http://gitt.io/badge.svg)](http://gitt.io/component/com.ti.androiddeviceyear

`$ gittio install com.ti.androiddeviceyear`

## Author

**Louis Quaintance**  
email: louisandkatherine10@gmail.com
