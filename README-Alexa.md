# Introduction
Alexa is Amazon's personal virtual assistant which listens to user's voice commands and responds with appropriate answers. Apart from conversing with the user, Alexa lets you play music from a variety of music streaming services. Alexa also helps you manage to-do lists and allows for voice-assisted shopping from Amazon.

# Device Configuration
* Before proceeding with device configuration, make sure you have read and followed `README-Getting-Started.md`.
* By default, when the firmware comes up it is un-provisioned. The device console should display the following lines in this mode:
```
I (xxx) conn_mgr_prov: Provisioning started with :
	service name = ESP-Alexa-xxxx
	service key =
```
You can use either the Android or iOS apps (links below) to provision your device to the desired Wi-Fi Access Point and associate the user's Amazon account with the device.
* [Android](https://github.com/espressif/esp-avs-sdk/releases)
* [iOS](https://github.com/espressif/esp-idf-provisioning-ios/tree/versions/avs)

# Demo
* Once the board boots up and successfully connects to the Wi-Fi network after provisioning, you will see a print "Alexa is ready", after which you can use either use "Rec" button on the board or say "Alexa" to start a conversation. For Tap-to-Talk, press and release the button and speak. The green LED glows when the microphone is active.
* You can connect any external speaker/headphone with 3.5mm connector to PHONE JACK to listen to responses.
* you can now ask any command like:
    * tell me a joke
    * how is the weather?
    * will it rain today?
    * Sing a song
    * Play TuneIn radio
    * Set volume level to 7
* Press and Hold "Mode" button for 3 seconds to reset the board to factory settings.

# Supported music streaming services
* Amazon Music
* Saavn (India)
* Pandora
* TuneIn Radio
* iHeart Radio

# Production notes
* In order to create Alexa-enabled commercial products, Amazon certified acoustic front-end has to be used. Please reach out to Espressif if you are looking to go to production.