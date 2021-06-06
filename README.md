Personal fork to try stamping out some errors to offer up for re-inclusion.

Original Readme below ---


# Custom Components for Home Assistant

## `ge_kitchen`
Integration for GE WiFi-enabled kitchen appliances.  So far, I've only done fridges and ovens (because that's what I
have), but I hope to to dishwashers next.  Because HA doesn't have Fridge or Oven platforms, both fridges and ovens are
primarily represented as water heater entities, which works surprisingly well.  If anybody who has other GE appliances
sees this and wants to pitch in, please shoot me a message or make a PR.  

Entities card:

![Entities](https://raw.githubusercontent.com/ajmarks/ha_components/master/img/appliance_entities.png)

Fridge Controls:

![Fridge controls](https://raw.githubusercontent.com/ajmarks/ha_components/master/img/fridge_control.png)

Oven Controls:

![Fridge controls](https://raw.githubusercontent.com/ajmarks/ha_components/master/img/oven_controls.png)

## What happened to `shark_iq`?

It's part of Home Assistant as of [0.115](https://www.home-assistant.io/blog/2020/09/17/release-115/)!
