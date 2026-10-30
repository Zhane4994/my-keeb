---
title: "My Keeboard"
github: "https://github.com/Zhane4994/my-keeb"
description: "A fully mechanical keyboard, created with the keeb docs!"
created_at: "(2026-09-10)"
total_time: "31h 36m"
---

I designed a mechanical keyboard from scratch with kicad pcb's and onshape cases. I also learned how to use the RMK firmware to create a functional keyboard. I did this project because I used to be into keyboards and I thought it would be super cool to not only learn more about how they work but how to design one.

# September 10, 2026: The Core Idea
<!-- fabricate:entry 1442 -->

Part I, PCB and Schematic design

I’m currently working on this at lunch. I have no idea what I’m doing lmao just following the guide. I have a slight idea of what I want to make. I am going to make it a 75% keyboard with a lcd screen and a knob. I just found out it’s supposedly due in a month golly. LOCK IN. This is my inspiration

<img width="1000" height="1000" alt="nmpc-yunzii-AL80-silver-mechanical-keyboard-2059385894" src="https://fabricate.hackclub-assets.com/0ff5068b769f6b87093c43093ca388eb02d3b338f0b1367379889005f29f9e3d/image-jpeg/4b981d7c-b0d8-4a5f-b995-72f44b38bd73.jpg" />

**Total time spent: 1h**

# September 10, 2026 (entry 2): Schematic Matrices and Initial PCB Design
<!-- fabricate:entry 1443 -->

Just got back from school. I’ll be working on this for the next few days hopefully I’m able to get to the coding soon.

<img width="2560" height="1440" alt="2222222222222" src="https://fabricate.hackclub-assets.com/44d4b221c7c57741bb9b9e62b3ef1dea8d15e69108de9d8c781029f8a21547b9/image-png/b1a61892-e35c-49a5-a3a9-4d38cfd75cdb.png" />

Just finished up the schematic matrices mostly.

<img width="2560" height="1440" alt="Screenshot 2026-09-10 at 7 05 09 PM" src="https://fabricate.hackclub-assets.com/86a8440f8d297795f0e51a00da1586d26c95c49037760bcee4ed97e38b9e88fa/image-png/9c6d1af0-39d8-4f61-81e8-9d979ac131e3.png" />

Just finished up the Schematic matrices

**Total time spent: 1h**

# September 10, 2026 (entry 3): Beginning the PCB Design
<!-- fabricate:entry 1444 -->

<img width="2560" height="1440" alt="Screenshot 2026-09-10 at 7 27 56 PM" src="https://fabricate.hackclub-assets.com/b3c540489445f767bfb940482216be22e161872ad2f9801f5675fbedfba50631/image-png/1702f90b-f916-472a-86df-9b3f6279caba.png" />

WOW. I’ve made up quite a bit of progress already and I’ve already thought of an idea of what I want my keyboard to be like. 1st, I want the entire keyboard to be a normal keyboard with no special shapes and a screen above the arrow keys. Now I’ve begun to create my PCB design.

**Total time spent: 1h**

# September 10, 2026 (entry 4): PCB Layout and Troubleshooting
<!-- fabricate:entry 1445 -->

I spend 2 hours working on the PCB. I had to restart because I messed up the schematic somehow and it took me a bit to get the layout of the keyboard right.

<img width="2560" height="1440" alt="Screenshot 2026-09-10 at 11 40 44 PM" src="https://fabricate.hackclub-assets.com/f817ca0f4baaaefc6d4934925894f351e7a6ec69cdffbee018f30d781dfc6a4c/image-png/67b196be-6ee8-4121-b6d5-2ca9d56d8d50.png" />

**Total time spent: 2h**

# September 11, 2026: Wiring the PCB
<!-- fabricate:entry 1446 -->

I’ve just spent one hour on just wiring alone. This is super time consuming

<img width="2560" height="1440" alt="Screenshot 2026-09-11 at 7 28 20 PM" src="https://fabricate.hackclub-assets.com/ec68281126ce1115b8da3982ef84a36f0dec74b151c7de02ba1766d7a5d72b4a/image-png/0057e37c-a682-487a-a63a-85c229f2d6c7.png" />

**Total time spent: 1h**

# September 11, 2026 (entry 2): Adding the Rotary Encoder and OLED Screen
<!-- fabricate:entry 1447 -->

I’ve spent a while just working on moving stuff around according to the DRC as I had some issues. I also added a Rotary encoder and a OLED screen. I forgot to screenshot yesterday so this is my finished PCB now. I had to rewire a bunch of stuff and the PCB is packed and there isn’t much room.

**Total time spent: 2h**

# September 11, 2026 (entry 3): Beginning the Case Design
<!-- fabricate:entry 1448 -->

I just began to make my case. It actually took me so long to find out how to get the bom.cvs files

<img width="2514" height="1276" alt="Screenshot 2026-09-11 at 11 09 13 PM" src="https://fabricate.hackclub-assets.com/1657adc25fe36cdd1dc58271a0a28c338b14a7dff192820adbacb2b89c6503ab/image-png/035b01f2-a5c1-4a07-9629-bdf18a817a9f.png" />

**Total time spent: 1h**

# September 12, 2026: Designing the Keyboard Case
<!-- fabricate:entry 1449 -->

Spent an hour creating the bottom half of my keyboard case and beginning to map out the key’s

<img width="2512" height="1277" alt="Screenshot 2026-09-12 at 11 47 04 PM" src="https://fabricate.hackclub-assets.com/a47abb9ed2a8042fb213e436b117f6ac7ee8fa7ce8b2e2b3929581313f30341f/image-png/d1f099cc-1501-4134-a438-05b252845b3a.png" />

I got through my process and realized that the tab, caps lock, shift, and control keys probably won’t work as I just randomly placed them. This is going to backtrack me all the way to a non wired PCB. Which will be annoying but I think it will be worth it just to get a keycap set that will actually look good on it.

**Total time spent: 2h**

# September 13, 2026: Learning About LED Matrices
<!-- fabricate:entry 1450 -->

I spend this hour mostly asking ai how a led matrix works and if its possible with the pico its actually so bad but now I’m beginning to create the matrix and fixed using the normal GND pin instead of the AGND pin.

<img width="2560" height="1440" alt="- 22922222290092" src="https://fabricate.hackclub-assets.com/a584325c70c3a8c20660784eb6d569a120e6ffbc2c855ff2dc8949fa4caff304/image-png/5c3b843f-d8d2-4b5b-81ad-e24c4be5fd7e.png" />

**Total time spent: 1h**

# September 13, 2026 (entry 2): Creating the LED Matrix
<!-- fabricate:entry 1451 -->

Spent one hour creating a LED matrix and create the PCB

<img width="2560" height="1440" alt="Screenshot 2026-09-13 at 7 27 45 PM" src="https://fabricate.hackclub-assets.com/f655b340de7f00d40beea3ec26e43aa181cad9f33099200d6b28d920b4236f3b/image-png/b088723f-d399-44e3-ab41-8bc6ad40d95c.png" />

**Total time spent: 1h**

# September 14, 2026: Choosing the Capacitors and Finalizing Key Switch Placement
<!-- fabricate:entry 1452 -->

I have spend today so far asking ai what to do about my capacitor situation because the ones I found on Aliexpress don’t have measurements of how apart the legs are and I didn’t think of just bending them if they are too close together so I’m just going to use radial 5mm

<img width="2560" height="1440" alt="Screenshot 2026-09-14 at 4 22 03 PM" src="https://fabricate.hackclub-assets.com/3fd9d74aae1837adcc268f0fc67d381f0ba9c61f0bf092e5c0a6b3762f8a52be/image-png/6134feeb-ab74-4dbf-ae9e-b528c4c516f9.png" />

Completed the key switch placement

**Total time spent: 1h**

# September 14, 2026 (entry 2): Placing Diodes and LEDs
<!-- fabricate:entry 1453 -->

<img width="2560" height="1440" alt="Screenshot 2026-09-14 at 7 28 04 PM" src="https://fabricate.hackclub-assets.com/8553a022af7702311f8a7d65ebb847851afe82f984666cf00d33fa08b45107b5/image-png/0ead25fb-4632-478a-8458-784e43538cbd.png" />

JEEZ. This actually took so long. I ended up taking 2 hours just to put in the diodes as well as all the LED in the right position. And I’m just starting wiring. This is going to be super hard and thanks to MD for letting me go off his keyboard as a reference point.

**Total time spent: 2h**

# September 15, 2026: Changing the Hot-Swap Socket Footprints
<!-- fabricate:entry 1454 -->

<img width="2560" height="1440" alt="Screenshot 2026-09-15 at 6 12 45 PM" src="https://fabricate.hackclub-assets.com/0e3feedfc203c663e0cbcd9bd5b6ff112d3f7da740bd560c1e607e278a5a90ad/image-png/ccc55052-184f-4370-964b-cb0ffc718a62.png" />

So I just found out that I need to set the footprint to a different one for hot swap sockets so now I have to redo all the placements again

**Total time spent: 1h**

# September 15, 2026 (entry 2): Reconsidering the PCB Layout
<!-- fabricate:entry 1455 -->

<img width="2560" height="1440" alt="Screenshot 2026-09-15 at 10 32 31 PM" src="https://fabricate.hackclub-assets.com/5e7c5e7e97cc0ee70b84eebe0e8bbea6fb73bede655052070b766e6d470279db/image-png/fa6bc44d-4a44-4f83-8ba5-55b0c5f94f1d.png" />

While looking through the examples in slack, I found out that I don’t actually have enough space for a plate between the pcb and the top of the switches thanks to the pico 😡. Also someone told me that the LED’s actually should be on the bottom layer. AFTER I WIRED THEM ALL. So great I think it will be a lot easier to just straight up restart again 😡

**Total time spent: 1h**

# September 16, 2026: Wiring the PCB with the Pico on the Back
<!-- fabricate:entry 1456 -->

<img width="2560" height="1440" alt="Screenshot 2026-09-16 at 5 32 16 PM" src="https://fabricate.hackclub-assets.com/43205f15c62d9a485dc6b5329b2ae328b1bff7d2df298f4f95fce94f7c0ce447/image-png/cc069078-8129-402a-841d-e85517b70110.png" />

I’ve spent today wiring out the PCB. It’s super complicated as I flipped the pico to the back and have to switch the pin locations on the schematic.

**Total time spent: 1h**

# September 20, 2026: Finishing the PCB Wiring
<!-- fabricate:entry 1457 -->

<img width="2560" height="1440" alt="Screenshot 2026-09-20 at 6 13 34 PM" src="https://fabricate.hackclub-assets.com/f031919a9900f8190de49c525e8ce867c6ea645521dcd63e6107bf5b93b222ea/image-png/d90422fb-86a4-4df5-a1b0-a8f0fa53a193.png" />

Pretty much finished my wiring. I took a forced break from my dad yesterday so lost some time there. I will try to complete by Wednesday or at least get to firmware.

**Total time spent: 1h**

# September 20, 2026 (entry 2): Completing the PCB and Starting the Case Design
<!-- fabricate:entry 1458 -->

I’ve finished my PCB and tweaked it halfway into the case design because I realized the resistor placement is not optimal(look up above. I wanted to do a gasket mount by making the inside of the case be under the pcb by 3 mm but a resistor and capacitor would be in the way and I think it would just be better to move them)
I also began my case design so here’s part II
Part II, Case design

**Total time spent: 1h**

# September 25, 2026: Developing the Keyboard Case
<!-- fabricate:entry 1459 -->

It’s been a couple of days. I forgot to document my process but I’ve been using guides and references and I’ve taken about 3 hours to complete my case.

<img width="2560" height="1440" alt="Screenshot 2026-09-25 at 6 41 36 PM" src="https://fabricate.hackclub-assets.com/863148b4885482659e902cd0d213bc7d7d6af257aa8951782608c3e1f68ee1ae/image-png/f0508569-da8e-4252-a490-ab9956b3e578.png" />

**Total time spent: 4h**

# September 26, 2026: Designing the Snap-Fit Case Mechanism
<!-- fabricate:entry 1460 -->

Today, I’ve spent about an hour. Brainstorming and thinking of ideas of how to snap fit the 2 housing parts together and I’ve come up with an idea. Once side will have holes that the top housing can go into with tabs

<img width="2560" height="1440" alt="image" src="https://fabricate.hackclub-assets.com/299d84d6ebcae886180ea3595bd976b26c9ab40279ce74dbe0a1d8a793f038d1/image-png/730faf98-f8ac-4c09-93c8-ac6a201b4d8d.png" />

<img width="2560" height="1440" alt="image" src="https://fabricate.hackclub-assets.com/712fb1869a525d0ce9b0d7e7e3f357fa257c0e76d225be5aaddcabf0f30c0235/image-png/940c2dfc-10f8-4306-be58-9048309f6621.png" />

And on the part of the case away from the user, there will be a notch in the base and a tab that will slide into it

<img width="2560" height="1440" alt="Screenshot 2026-09-26 at 2 42 32 PM" src="https://fabricate.hackclub-assets.com/fd34cd287c52adb70b4c1e242d391407c09c158b9099b6c54ee1239abe52fb1e/image-png/6f963b11-ada4-44a5-8bf8-2986749c1ac5.png" />

<img width="2560" height="1440" alt="image" src="https://fabricate.hackclub-assets.com/a5e338a450de52bfd793fda599e1909508375ac002d3dc19300a3d977897fb56/image-png/93833ee4-27d5-4c16-83ef-c4cb188cc2ae.png" />

Also It’s a triangle just so its a bit easier to take off but won’t come off just with use.

<img width="2560" height="1440" alt="Screenshot 2026-09-26 at 3 53 06 PM" src="https://fabricate.hackclub-assets.com/bc4e0a108b9fbde7e9af0dda3f1bb49f8a010d28d8edecc705a5197e268a8f25/image-png/6f3ea1b7-0236-45a4-b426-d1e893030855.png" />

Completed Case

**Total time spent: 1h**

# September 26, 2026 (entry 2): Starting the Firmware
<!-- fabricate:entry 1461 -->

Part 3, Firmware

I've spend almost 2 hours looking around the docs and figuring out how this works. The docs were pretty confusing because i have no clue what they are talking about lol

<img width="2560" height="1440" alt="Screenshot 2026-09-26 at 3 53 06 PM" src="https://fabricate.hackclub-assets.com/bc4e0a108b9fbde7e9af0dda3f1bb49f8a010d28d8edecc705a5197e268a8f25/image-png/82f7da3f-f10e-4208-ab92-d2d5d67486ce.png" />

**Total time spent: 2h**

# October 2, 2026: Completing the Keyboard
<!-- fabricate:entry 1462 -->

And that is my keyboard complete. I have 2 days left so i'm going to submit asap!

<img width="2497" height="1269" alt="Screenshot 2026-10-02 at 9 41 14 PM" src="https://fabricate.hackclub-assets.com/3801e526a3d7959809ae5357cccf369feda43a809806fbf38c82c011b129b5e3/image-png/37ece5fb-3d84-4fe5-870b-5933d0c46e67.png" />

**Total time spent: 1h**

# October 28, 2026: Re making my entire pcb
<!-- fabricate:entry 1500 -->

So I realized after checking through my pcb again, I made my diode all through hole diodes instead of surface mounted ones :/. Its not all bad because I want to use a different chip too, the waveshare ESP32-S3-Devkit which supports wireless! I believe this means it has great upgradability paths

What this means: I'm going to have to recreate every file after the pcb which may take me a while.
![](https://fabricate.hackclub-assets.com/b2b1f54a7d72e35f5684a12b300e1064a49e76d3ed30437527ac8487a97599c1/image-png/Screenshot%202026-10-28%20at%2010.17.39%E2%80%AFPM.png)

**Total time spent: 6m**

# October 28, 2026 (entry 2): Laid Out PCB & finished revised schematic
<!-- fabricate:entry 1503 -->

For this session, I was able to redo my schematic completely, replacing the current diodes with 1n4148W's and implemented a nice!view and a ESP32 board. (I made both the symbol and footprint for the esp32 board before!)

![](https://fabricate.hackclub-assets.com/fa5f039f032a91350b0e93fe806fd9144ee1e48c4868c9cab696aabf1bc94310/image-png/Screenshot%202026-10-28%20at%2011.54.28%E2%80%AFPM.png)
![](https://fabricate.hackclub-assets.com/3b702d052f97a3aa68081ebd1ff28dfacb5a195d92edee5e780040ad404bb253/image-png/Screenshot%202026-10-29%20at%2012.02.38%E2%80%AFAM.png)

**Total time spent: 1h**

# October 28, 2026 (entry 3): PCB Diode Placements
<!-- fabricate:entry 1505 -->

I spent this time ordering up the LEDs to make it easier for me later to put them in. I also placed in the diodes into place and changed up some of the footprints. This took a lot of time mostly because of how small they were and the LEDs were put in super crammed together which was pretty hard to separate.


![](https://fabricate.hackclub-assets.com/96d85e59dbf01429dced607fa645294aad1238a3d997e66f804330b444a4a678/image-png/Screenshot%202026-10-29%20at%2012.39.10%E2%80%AFAM.png)


![](https://fabricate.hackclub-assets.com/af834482f20ea841e881f838fe45e85522396b8e4c88ffd28cbc1391dfab3a59/image-png/Screenshot%202026-10-29%20at%2012.38.10%E2%80%AFAM.png)

**Total time spent: 1h 30m**
