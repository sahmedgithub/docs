---
layout: default
title: Connect to WiFi
breadcrumb: Connect to WiFi
amazon_ads: true
comments: true
---

# Connect to WiFi
Before wiring and mounting your device, you first need to set up WiFi and establish the network connection to 
SmartThings.

1. Power on the device for the first time by plugging in a micro-USB cable and connecting it
 to any USB charger or computer. Or you can use any 6V to 24V DC power adapter plugged into the circular power port on
  the device base.
  
    ![](/assets/images/power-plugs.jpg){:class="img-callout"}

1. When the Konnected device is powered on you should see a slow blinking blue LED indicating that it's trying to 
connect to WiFi. Until WiFi is configured, the device will broadcast its own WiFi network named like 
`konnected-security_XXXXXX` for configuration.

    ![](/assets/images/Screenshot_20170710-225505.png){:class="img-callout"}

1. Connect to this WiFi network with your smartphone or computer, then open a web browser to 
 **[http://192.168.4.1](http://192.168.4.1)**
 
    ![](/assets/images/Screenshot_20170710-225643.png){:class="img-callout"}

1. Select your wireless network from the drop-down menu and enter your WiFi password. After tapping Save, the device
 will connect to your home WiFi network and the LED will stop blinking and be **solid blue** or **turn off**.

    _Note:_ The wireless network must be on the same LAN/subnet as your SmartThings hub.
    
    _Note:_ The device only supports 2.4GHz (2G) wireless networks
 
1. Un-plug and re-plug in the device causing it to reboot. The blue LED will blink for a few seconds and then 
**turn off**, indicating that it's connected to Wifi and ready to be added to your SmartThings network.
 
##### **Next Step:** [Enable SmartThings GitHub Integration](/security-alarm-system/installation/github-integration) 
 