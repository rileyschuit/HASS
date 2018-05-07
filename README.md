[![Build Status](https://travis-ci.org/rileyschuit/HASS.svg?branch=master)](https://travis-ci.org/rileyschuit/HASS)  

# Home Assistant configuration  
  
Currently running version 0.49.0  
  
Using the following:  
[Unifi Cameras](https://www.home-assistant.io/components/camera.uvc/)  
[NEST Thermostat and Protect](https://home-assistant.io/components/nest/)  
[Slack via shell commands for webhooks](https://home-assistant.io/components/shell_command/)  
[Ubiquti Unifi for device tracking](https://home-assistant.io/components/device_tracker.unifi/)  
  
A few example summaries:  
1. Input boolean for setting thermostat to eco and turning off a zwave switch. Additional automation for turning things back at 4 PM.  
2. Input boolean for receiving alerts.
3. Timer for light after it's turned on.  
4. Automation action to use shell scripts.  Shell script to POST to slack webhook for messaging 
5. (DRAFTED) Timer for multiple lights (two swtiched) for when ether one of two garage doors open (two binary switches).
  
### Documentation jumps:
[Storing secrets](https://home-assistant.io/docs/configuration/secrets/)
