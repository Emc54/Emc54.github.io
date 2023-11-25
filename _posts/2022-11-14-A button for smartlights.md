---
title: A button for smart lights
date: 2022-11-14 19:14:54 +0000
categories: #[TOP_CATEGORIE, SUB_CATEGORIE]
tags: #[TAG]     # TAG names should always be lowercase
---

You can do two things when buying a knock-off product:

1. Understand that you might be getting something inferior and accept it.
You did willingly spend less money, after all. If you don't want to do that though...
2. You can turn it into a project — to create a (frankly overcomplicated) mess to cover up the inferiorities of the knock-off item you have purchased.

Will the second approach cost more money than the original project?
_Almost certainly._
Will it be a fun teaching experience?
It was in this case.
So I can at least live with the illusion that I've made good decisions for one more day.

## Smart lights - The Problem

The smart lights I currently own are not the Philips ones that are more commonly expected when one talks about smart lights.
Now there are many off-brand smart lights, and I didn't spend time comparing differences.
I bought what was at a reasonable price at the time, especially with the chip shortage crisis that meant that Philips lights were 2-3x their usual price.
I said to myself I'd upgrade once the ones I got burned out.

The problem was that these lights did not handle being disconnected from the network gracefully.
If they couldn't find a connection, they would go into their default reconnection mode.
That would have been fine if that mode wasn't to flash the brightest white light once a second.

The upshot of this was that the physical light switch became practically useless, and I would have to control my lights exclusively through my phone.
This is because the physical light switch cuts the wifi connection from the bulbs and they go into reconnection mode immediately as they come back up instead of looking for the network first.

## The Solution

The app to control the lights has a turn-off function.
Invoking that would be good enough.
I just had to figure out a way to translate the function call from the app, into a physical switch on my wall.
It seemed simple enough at the time, and in retrospect it is, just the approach could be more elegant.
But this was supposed to be a quick project, so the first (bodgy) solution is the final one, to match the quality of the original product.

## The Parts

1. [IFTTT](https://ifttt.com/) - Handles applet requests using WebHooks.
2. [SmartLife API](https://ismartlife.me/) - The app used by the lights manufacturer.
3. [ESP8266 NodeMCU](https://en.wikipedia.org/wiki/NodeMCU) - The (last) microcontroller used for the button control.

## Initial Attempts

## Prototype

## Product Management

The hackiest of equipment can look professional if the box is well-designed.
I gather more evidence to confirm this claim, the more I investigate electronics by taking them apart.
So naturally, to finalise this project I needed a nice box.

![Bottom case](/assets/img/smart-button/case-bottom.png){: w="300" }
_Bottom part of the case_

![Top case](/assets/img/smart-button/case-top.png){: w="300" }
_Top part of the case_

## Outcome

![open button](/assets/img/smart-button/button-no-cover.jpg){: w="200" }

![final button](/assets/img/smart-button/button-on-wall.jpg){: w="200" }