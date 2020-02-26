As this is an evolution of heater-controller project read that repository first since they have a lot of things in common: https://github.com/mbc99/heater-controller

In this case the project is split into two main components:
*A controller: that sits on the gas heater room and does the same function as heater_controller project except that:
	*It lacks (or doesn't need and RTC)
	*It has two RS232 lines (based on MAX3232 iC)
	*It lacks a screen and buttons
*A sensor/comunication module located on the dinning room. This module acomplishes several functions:
	*Sense the ambient temperature
	*Control when to activate the heating, DHW etc.
	*Send and recieve all the information via MQTT and a GSM module




## Controller