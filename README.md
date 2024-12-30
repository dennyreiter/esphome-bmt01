# esphome-bmt01
Work in progress to try and interface a Sonoff BMT01 BBQ Meat Thermometer to Home Assistant

## The device
The Sonoff BMT01 is a BBQ Meat Thermometer that supports up to four probes and communicates via Bluetooth back to the eWeLink mobile app.

https://sonoff.tech/product-document/gateway-and-sensors-doc/bmt01-doc/

I don't want another app to use, and want it to integrate with Home Assistant.

## Bluetooth
I've attempted to figure out the Bluetooth characteristics used, but so far no luck

## ESPhome
This is my YAML so far. The two vendor specific characteristics (bbb1 & bbb3) both just return 0x88 (136)

