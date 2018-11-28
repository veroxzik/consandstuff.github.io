---
title: GROOVE COASTER CON
---

# Groove Coaster PC (DIY)

Written by [Verox Zik](https://github.com/veroxzik/).

>Last update: November 27, 2018
- Initial Release

Many thanks to:

- [KnucklesLee](http://knuckleslee.blogspot.com/2018/04/groovecoaster.html) for the original idea and prototype (and many revisions).

- Lizard_beans for starting this github and the Cons&Stuff Discord

### TO DO List:

- Finish this guide lol

<hr>

# Index

1. Introduction
2. Parts List / Hardware
3. Tools
4. Instructions

<hr>

## Introduction

The goal of this guide is to provide instructions on how to construct a simple Groove Coaster (GC) controller, suitable for use with PC and in particular, the Steam release of Groove Coaster.

This will mostly be a collection of parts for you to buy and some example code. Case size will vary depending on whether you want a compact controller, or one that is arcade accurate, and case construction is well covered in other projects on this site.

<hr>

## Part List / Hardware

As always when buying online, I would suggest you do some research before blindly buying anything suggested here. You may find better deals. I am only here to get you started.

* [8-way Flight Joystick](https://www.aliexpress.com/item/8-Way-Flight-Joystick-with-Trigger-Top-Fire-Button-For-Arcade-game/32863002564.html) x2

* [60mm Arcade Button](https://www.aliexpress.com/item/MAYITR-Push-Button-Arcade-Button-LED-Light-Switch-Colorful-60mm-Big-Round-Arcade-Video-Game-Player/32884099711.html) x2

You will find that both of these have horrible microswitches. Therefore, we'll need to buy some better ones.

To replace the switches in the joystick, I chose the *Omron V-152-1A5*. This is a somewhat pricy option, but I believe any 200gf lever microswitch will suffice. Perhaps check out fightstick suppliers.
These are available at:
* [Allied Electronics](https://www.alliedelec.com/omron-electronic-components-v-152-1a5/70355271/)
* [Mouser](https://www.mouser.com/ProductDetail/Omron-Electronics/V-152-1A5?qs=jlWqeHNmHbSoRFViILdGxw%3D%3D)

To replace the switch on the button, I would suggest a 25g microswitch and 50g spring.

* [Microswitch](https://istmall.co.kr/us/goods/goods_view.php?goodsNo=1009992411)
* [Spring](https://istmall.co.kr/us/goods/goods_view.php?goodsNo=1009992332)

The choice of microcontroller is up to you. I had a Teensy 2.0 lying around, so I went with that. You could pick that, a Teensy 3.2, an Arduino Leonardo / clone, an Arduino Micro / clone, or many others.

In a departure from KnucklesLee's design, I chose to use 3D printed components for mounting the button to the joysticks (this is because I had access to a 3D printer).

If you're using US Standard:
* [Base Mount](/files/Shaft Mount Base v2.stl) x4
* [Button Mount](/files/Shaft Mount Top.stl) x2

If you're using Metric:
* [Base Mount (Metric)](/files/Shaft Mount Base v2 Metric.stl) x4
* [Button Mount (Metric)](/files/Shaft Mount Top Metric.stl) x2

In addition, you'll need the following hardware:

* [4-40 x 2" Aluminium Female Standoff](https://www.mcmaster.com/#catalog/91780A040) x8
* [4-40 x 0.5" Flat Head Screws](https://www.mcmaster.com/#catalog/90273A110) x16
* [4-40 x 0.75" Pan Head Screws](https://www.mcmaster.com/#catalog/90272A113) x4
* [4-40 Hex Head Nuts](https://www.mcmaster.com/#catalog/90480A005) x4

If you're using the metric versions, use M3 bolts instead. Ensure your flat heads are 90° countersink angle.

<hr>

## Tools

* Soldering Iron (probably)
* Solder (60/40 rosin core is easiest)
* Crimper (if you use quick disconnects)
* Wire cutters
* Wire strippers
* Some way to cut metal, like a hacksaw or rotary tool

<hr>

## Instructions

To be written

