
<h1 align='center'>X201</h1>

---
Repo closed due to others beating me to it, follow them for updates on framepads, sorry.
https://www.reddit.com/r/thinkpad/comments/1gpozs8/update_on_x41_w_framework_motherboard/
---

**Last update: 25 july 2024**

<img src='X200-blowup.png' align='center' width='100%'/>

Fooling around with my X220 repo had me wanting more,
so i've decided to mobo transplat an Framework mainboard into a X201 chassie
with a few mods/upgrades.
My new go to distro for the time being is "Pop_OS" because it's polished.
feels well integrated and has emense support.

TLDR: Mission is to drop an framework mobo into an X201( basically a Framework/nb51 X2100 ) 

<img src='https://evergreenfevers.neocities.org/pikaconstruct.gif' align='center' width='15%'/>

## Stuff 2do:
* **Red ThinkLight mod**
* **Internal USB** - attach RTL8812AU. 
* **Speaker mod** - Samsung note 10 or Ipad 11" pro speakers
* **Mechanical keyboard fold out feet** - for extra cooling
* **Antenna mod** - Good ol mods
* **Custom I/O** - still looking into this
* **Framework mainboard bracket** - Get mobo from their outlet
* **convert CN2 keyboard bus connecter** - Keeping the lenovo keyboard ofc.
* **Adapt LVDS panel for mainboard** - (Convert eDP to LVDS if necessary)
* **rework the base** - the base need to account for the boardswap aswell as cooling redirection.
* **Palmrest** - Remove touchpad and get pure palmrest.

<img src='mainboard.jpeg' align='center' width='75%'/>
Get the board from https://frame.work/dk/en/outlet

## Gameplan

<img src='sketch.jpg' align='center' width='70%'/>

mainboard diamentions:
233mm x 112mm x 6.8mm

X201 mobo diamentions:
180mm x 145mm x 16mm(175mm depth with fan)

### I/O
Thanks to based Apple for making the Type C dongles obligatory on the daily - 
then i get an nice selection for I/O on each side of the x201 as an alternative for making daugtherboard.

<img src='dongle.jpg' align='center' width='100%'/>

## Issues
* **Adrino Controller clone** - finding these for the keyboard, can be tricky
* **keep the memory slot door usable**
* **Refitting/Drilling ports for the base/mainboard**
* **Firmware blobs might disagree**
* **battery BMS communication**
* **Inner dimentions** - some measurements might not add up
* **Some mainboard ports needs redirection** - like the battery connetor being on the opposit side.


<img src='https://i1.wp.com/www.xyte.ch/wp-content/uploads/2020/06/DSC1323-scaled.jpg?ssl=1&resize=1707%2C1707' align='center' width='80%'/>

I might use parts of Latitude 7330 Rugged Extreme. idk yet.

Resources:
* https://www.instructables.com/Make-a-ThinkPad-keyboard-USB-adapter-with-Arduino/
* https://www.rowsum.com/the-ultimate-guide-to-reading-schematics-uncover-the-blueprint-of-electronics/
* https://www.xyte.ch/mods/x210-x2100/
* https://www.reddit.com/r/thinkpad/comments/s71mcx/i_3d_printed_a_new_trackpoint/ - i just want it
* https://en.wikipedia.org/wiki/Pop!_OS



