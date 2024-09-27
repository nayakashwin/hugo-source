---
title: "Remote Controlled Lawn Mower - Analysis - Motor Controller"
date: 2024-09-27T05:58:48-05:00
description: "Exploring motor controller choices"
tags: [robotics, BLDC, bldc-controller, cheap, lawn, mower]
---

This article explores the different motor controller choices.
<!--more-->

## Motor controllers considered
1. Hoverboard motor controller
2. ZS-X11H
3. ZS-X11F
4. ODrive V3.6 - 56v

## Hoverboard motor controller
### Pros
1. Relatively Cheap
2. Easy to source new or second hand from used hoverboard
3. Can be hooked up directly to an RC controller

### Cons
1. Too many versions to keep track of
2. Large size
3. Limited cooling options

## ZS-X11H
### Pros
1. Very Cheap
2. Easy to source from AliExpress, eBay or Amazon
3. Precise motor control as it supports hall sensors

### Cons
1. Enabling PWM control needs minor soldering
2. Needs seperate MCU to control

## ZS-X11F
### Pros
1. Very Cheap
2. Easy to source from AliExpress, eBay or Amazon

### Cons
1. Does not have hall sensors making precise control impossible
2. Needs seperate MCU to control

## ODrive V3.6 - 56v
### Pros
1. Highly configurable

### Cons
1. Only clones available from AliExpress or eBay hence what you get may or may not work
2. No longer supported
3. Very expensive

## Conclusion
The hoverboard motor controller was good but very bulky and for safety reasons should not be used directly with an RC controller. The ODrive was my favourite but its expensive and of the 4 boards ordered only 1 worked flawlessly on both channels. The ZS-X11F does not support hall sensors hence was eliminated as a choice almost immediately but only time will tell if I need to reconsider this in the future. All things considered ZS-X11F will probably be my final pick. I still need to get the PWM working with this board.