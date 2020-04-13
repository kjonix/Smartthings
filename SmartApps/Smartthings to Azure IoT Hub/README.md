**This Smartthings SmartApp requires basic knowledge about Azure IoT Hub.**

I will here give some quick tips, not an installation guide.

After installing the SmartApp you need to enter Azure IoT Hub Uri and SAS token in the App Setting area. I recommend using Visual Studio Code with the IoT plugin to get these variabels. 

Right click on your device and choose «Generate Code»  to get the URI. The URI looks like this: «https://xxxx.azure-devices.net/devices/Smartthings/messages/events?api-version=2018-06-30»

Right click on you device and choose «Generate SAS token for device». The SAS token looks like this:
«SharedAccessSignature sr=xxxx.azure-devices.net%2Fdevices%2FSmartthings&sig=xxxx&se=xxxxx»

Thanks to Sam Cogan and Ben Crouse for your work on the Azure Event Hub SmartApp. 

