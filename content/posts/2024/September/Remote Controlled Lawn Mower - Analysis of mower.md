---
title: "Remote Controlled Lawn Mower - Analysis of mower"
date: "2024-09-11"
description: "Exploring how to covert a gasoline lawn mover to a remote controlled lawn mower"
tags: [robotics, BLDC, bldc-controller, cheap, lawn, mower]
---

This article shares intent to convert a gasoline lawn mover to a remote controlled lawn mower and what questions need to be answered to proceed with the design.
<!--more-->

## Reusable Parts of a Lawn Mower
1. Deck
2. Gasoline engine with fuel tank and cable start

## Parts of a Lawn Mower which cannot be used
1. Wheels
2. Pushbar
3. Transmission

## Deck

The deck for the lawn mower I got is made of steel. It has a few rust spots but nothing too bad as the previous owner did not do a lot of mowing. This can be a good base to install an electric motor with wheels or a BLDC motorwith integrated wheels (e.g. howerboard wheels).

## Gasoline engine with fuel tank and cable start

The gasoline engine engine has an inbuilt fuel tank along with a cable start. The engine does work. Its in rough shape and might need some TLC. Needs new spark plugs. The carburetor does need some tuning as it generates some smoke. I am hoping the engine does not need any major investments like pistons, rings etc.

## Wheels

All 4 wheels are made of plastic and in very rugh shape. 1 wheel is broken. These wheels cannot be used as the entire wheel adjustment mechanism is rusted and it took me a while to remove the wheel and the adjuster.

## Pushbar

The pushbar is in good shape. However, for a remote controlled mower it may serve no purpose. For now I don't think we can do much with it.

## Transmission

This is a walk-behind lawn mower. The transmissions in these systems are pretty rudimentary. The transmission powers the back wheels only and both wheels seem to engage at the same time. Its in bad shape as well and cannot be reused since we want the entire lawn mower to turn on a dime.

## Design Decisions

So now that we have the mower there are a couple of design decisions which need to be made. 

For example: -
1. What kind of wheels to use to drive the mower?
2. What kind of motor controller do we need to use? 
3. Would the mower use 4 driving wheels or 2 driving wheels with steering?
4. What kind of batteries to use to drive the mower?
5. What kind of remote control to use to drive the mower?
6. What kind of fail safes would we implement to ensure the mower can be safely stopped?
7. Do we wish to install cameras for a head unit?
8. How would we keep the noise/emf from the engine from messing the eletronics?
9. What kind of navigation system we wish to implement?
10. Do we want this mower to be autonomous?
11. What kind of microcontroller do we wish to use?
