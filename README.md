# Cybersecurity-Guide
![](https://github.com/PratyayMallik1006/Cybersecurity-Guide/blob/main/images/header.png)
In last few years I had the oppurtunity to learn about cybersecurity, and what I have realised is that one of the most effective way to protect ourself from hackers is to be aware of cybersecurity, when we know in what ways a hacker can exploit our systems we can figureout ways to protect our systems. So in this repository I will me compiling all common ways a hacker can attack on a system and way to protect us from those attacks.
You will be suprised to know how scary easy it is to hack a system, even some amature kid without core knowledge of IT can easily hack, just by using free tools.

<h1><i>Legal disclaimer:</i></h1>
The resources provided in this repository is for purely educational purpose. Do not hack into any system without owner's permission. Developer(s) assume no liability and are not responsible for any misuse or damage caused by this resource. It's the end user's responsibility to obey all applicable local, state and federal laws. 

# i. Hardware hacking devices
## 1.Rubber ducky or Bad USB
[![rubber ducky](https://github.com/PratyayMallik1006/Cybersecurity-Guide/blob/main/images/rubber-ducky.PNG)](https://www.youtube.com/watch?v=sbKN8FhGnqg)
Usually most of us don't think twice before connecting a USB device (like a USB flash drive or a power bank) to our systems, as we are very much used to these devices and that what makes rubber ducky so dangerous. It is a USB device that could minic a HID or Human Interface Device like a keyboard, exploiting the system's trust on it's users.
<br>
Being able to minic a keybord it could type all kinds of commands.
<br>
Rubber Ducky is made and sold by Hak5 (https://shop.hak5.org/products/usb-rubber-ducky-deluxe).
<br>
Rubber Duckies are used in one of two ways:
- Leave it near target, hopping trget might plug it in, out of curiosity
- If the target leaves the system unlocked for some time the attacker plug it in
<br>
The attacker needs to set up the payload before the attack. Which can be easily downloaded from github (https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Payloads).
<br>
The avalable payloads include:

- Pranks like rickroll
- revese shell attacks (in simple words getiing remote access of target machine from internet)
- password stealler

Attcker can eaily create their own scripts also.As you can imagine the possibilities are endless, afterall you can mimic to be a user's keyboard.

### DIY Rubber ducky
Now rubber ducky is a bit expensive($50) and it may not be available in many countries also there is a risk of loosing it after attacking, so you might think it's quite unlikely that someone will hack an ordinary user with a rubber ducky, well it can esily made using affordable microcontrollers like Raspberry pi pico & Digispark Attiny85.
