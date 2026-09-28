Part I, PCB and Schematic design
Day 1 Hour 1
I’m currently working on this at lunch. I have no idea what I’m doing lmao just following the guide. I have a slight idea of what I want to make. I am going to make it a 75% keyboard with a lcd screen and a knob. I just found out it’s supposedly due in a month golly. LOCK IN. This is my inspiration
<img width="1000" height="1000" alt="nmpc-yunzii-AL80-silver-mechanical-keyboard-2059385894" src="https://github.com/user-attachments/assets/4b981d7c-b0d8-4a5f-b995-72f44b38bd73" />


Day 1 Hour 2
Just got back from school. I’ll be working on this for the next few days hopefully I’m able to get to the coding soon.
<img width="2560" height="1440" alt="2222222222222" src="https://github.com/user-attachments/assets/b1a61892-e35c-49a5-a3a9-4d38cfd75cdb" />

Just finished up the schematic matrices mostly.
<img width="2560" height="1440" alt="Screenshot 2026-09-10 at 7 05 09 PM" src="https://github.com/user-attachments/assets/9c6d1af0-39d8-4f61-81e8-9d979ac131e3" />

Just finished up the Schematic matrices
Day 1 Hour 3
<img width="2560" height="1440" alt="Screenshot 2026-09-10 at 7 27 56 PM" src="https://github.com/user-attachments/assets/1702f90b-f916-472a-86df-9b3f6279caba" />

WOW. I’ve made up quite a bit of progress already and I’ve already thought of an idea of what I want my keyboard to be like. 1st, I want the entire keyboard to be a normal keyboard with no special shapes and a screen above the arrow keys. Now I’ve begun to create my PCB design.
Day 1 Hour 4&5
I spend 2 hours working on the PCB. I had to restart because I messed up the schematic somehow and it took me a bit to get the layout of the keyboard right. 
<img width="2560" height="1440" alt="Screenshot 2026-09-10 at 11 40 44 PM" src="https://github.com/user-attachments/assets/67b196be-6ee8-4121-b6d5-2ca9d56d8d50" />

Day 1 Hour 6
I’ve just spent one hour on just wiring alone. This is super time consuming
<img width="2560" height="1440" alt="Screenshot 2026-09-11 at 7 28 20 PM" src="https://github.com/user-attachments/assets/0057e37c-a682-487a-a63a-85c229f2d6c7" />

Day 2 Hour 7&8
I’ve spent a while just working on moving stuff around according to the DRC as I had some issues. I also added a Rotary encoder and a OLED screen. I forgot to screenshot yesterday so this is my finished PCB now. I had to rewire a bunch of stuff and the PCB is packed and there isn’t much room.
Day 2 Hour 9
I just began to make my case. It actually took me so long to find out how to get the bom.cvs files
<img width="2514" height="1276" alt="Screenshot 2026-09-11 at 11 09 13 PM" src="https://github.com/user-attachments/assets/035b01f2-a5c1-4a07-9629-bdf18a817a9f" />

Day 2 Hour 10&11
Spent an hour creating the bottom half of my keyboard case and beginning to map out the key’s
<img width="2512" height="1277" alt="Screenshot 2026-09-12 at 11 47 04 PM" src="https://github.com/user-attachments/assets/d1f099cc-1501-4134-a438-05b252845b3a" />

I got through my process and realized that the tab, caps lock, shift, and control keys probably won’t work as I just randomly placed them. This is going to backtrack me all the way to a non wired PCB. Which will be annoying but I think it will be worth it just to get a keycap set that will actually look good on it.
Day 3 Hour 12
I spend this hour mostly asking ai how a led matrix works and if its possible with the pico its actually so bad but now I’m beginning to create the matrix and fixed using the normal GND pin instead of the AGND pin.
<img width="2560" height="1440" alt="- 22922222290092" src="https://github.com/user-attachments/assets/5c3b843f-d8d2-4b5b-81ad-e24c4be5fd7e" />


Day 3 Hour 13
Spent one hour creating a LED matrix and create the PCB
<img width="2560" height="1440" alt="Screenshot 2026-09-13 at 7 27 45 PM" src="https://github.com/user-attachments/assets/b088723f-d399-44e3-ab41-8bc6ad40d95c" />

Day 4 Hour 14
I have spend today so far asking ai what to do about my capacitor situation because the ones I found on Aliexpress don’t have measurements of how apart the legs are and I didn’t think of just bending them if they are too close together so I’m just going to use radial 5mm 
<img width="2560" height="1440" alt="Screenshot 2026-09-14 at 4 22 03 PM" src="https://github.com/user-attachments/assets/6134feeb-ab74-4dbf-ae9e-b528c4c516f9" />

Completed the key switch placement
Day 4 Hour 15&16
<img width="2560" height="1440" alt="Screenshot 2026-09-14 at 7 28 04 PM" src="https://github.com/user-attachments/assets/0ead25fb-4632-478a-8458-784e43538cbd" />

JEEZ. This actually took so long. I ended up taking 2 hours just to put in the diodes as well as all the LED in the right position. And I’m just starting wiring. This is going to be super hard and thanks to MD for letting me go off his keyboard as a reference point.
Day 5 Hour 17
<img width="2560" height="1440" alt="Screenshot 2026-09-15 at 6 12 45 PM" src="https://github.com/user-attachments/assets/ccc55052-184f-4370-964b-cb0ffc718a62" />

So I just found out that I need to set the footprint to a different one for hot swap sockets so now I have to redo all the placements again
Day 5 Hour 18
<img width="2560" height="1440" alt="Screenshot 2026-09-15 at 10 32 31 PM" src="https://github.com/user-attachments/assets/fa6bc44d-4a44-4f83-8ba5-55b0c5f94f1d" />

While looking through the examples in slack, I found out that I don’t actually have enough space for a plate between the pcb and the top of the switches thanks to the pico 😡. Also someone told me that the LED’s actually should be on the bottom layer. AFTER I WIRED THEM ALL. So great I think it will be a lot easier to just straight up restart again 😡
Day 6 Hour 19
<img width="2560" height="1440" alt="Screenshot 2026-09-16 at 5 32 16 PM" src="https://github.com/user-attachments/assets/cc069078-8129-402a-841d-e85517b70110" />

I’ve spent today wiring out the PCB. It’s super complicated as I flipped the pico to the back and have to switch the pin locations on the schematic.
Day 7 Hour 20
<img width="2560" height="1440" alt="Screenshot 2026-09-20 at 6 13 34 PM" src="https://github.com/user-attachments/assets/d90422fb-86a4-4df5-a1b0-a8f0fa53a193" />


Pretty much finished my wiring. I took a forced break from my dad yesterday so lost some time there. I will try to complete by Wednesday or at least get to firmware.

Day 7 Hour 21
I’ve finished my PCB and tweaked it halfway into the case design because I realized the resistor placement is not optimal(look up above. I wanted to do a gasket mount by making the inside of the case be under the pcb by 3 mm but a resistor and capacitor would be in the way and I think it would just be better to move them)
I also began my case design so here’s part II
Part II, Case design
Day 9 Hour 22-25
It’s been a couple of days. I forgot to document my process but I’ve been using guides and references and I’ve taken about 3 hours to complete my case.
<img width="2560" height="1440" alt="Screenshot 2026-09-25 at 6 41 36 PM" src="https://github.com/user-attachments/assets/f0508569-da8e-4252-a490-ab9956b3e578" />

Day 10 Hour 26
Today, I’ve spent about an hour. Brainstorming and thinking of ideas of how to snap fit the 2 housing parts together and I’ve come up with an idea. Once side will have holes that the top housing can go into with tabs
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/730faf98-f8ac-4c09-93c8-ac6a201b4d8d" />


<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/940c2dfc-10f8-4306-be58-9048309f6621" />



And on the part of the case away from the user, there will be a notch in the base and a tab that will slide into it
<img width="2560" height="1440" alt="Screenshot 2026-09-26 at 2 42 32 PM" src="https://github.com/user-attachments/assets/6f963b11-ada4-44a5-8bf8-2986749c1ac5" />

<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/93833ee4-27d5-4c16-83ef-c4cb188cc2ae" />

Also It’s a triangle just so its a bit easier to take off but won’t come off just with use.

<img width="2560" height="1440" alt="Screenshot 2026-09-26 at 3 53 06 PM" src="https://github.com/user-attachments/assets/6f3ea1b7-0236-45a4-b426-d1e893030855" />


Completed Case
Part 3, Firmware
Day 11 Hour 27-29
I've spend almost 2 hours looking around the docs and figuring out how this works
<img width="2560" height="1440" alt="Screenshot 2026-09-26 at 3 53 06 PM" src="https://github.com/user-attachments/assets/82f7da3f-f10e-4208-ab92-d2d5d67486ce" />
