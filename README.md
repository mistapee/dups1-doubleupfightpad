DupsONE-[point5]

The layout is exactly the same as DUPSone, but with additional tactile switches up the top. Thewidth is the same, but now it's a bit shorter. 

The two tactile (little black round switches) to the right are S1 and S2 (as you may know by now GP2040-CE webconfig is accessed by holding s2+b3+b4 where the pad resets and the webconfig is served up on 192.168.7.1)

The two tactile switches to the left are set as A1 and A2 in GP2040-CE, you may want to change these in the webconfig under GPIO configuration.

In GPIO config you will see that 2 different GPIO have been set to 'up', and you can change it.

Just as the previous A=B1, B=B2, X=B3, Y=B4, LB=L1, RB=R1, LT=L2, RT=R2
So webconfig reset is s2+X+Y. Note, that is only as I have sent it flashed to be that. The default GPIO specified by GP2040-CE for each button assignment is clarified on their site - if you need to access webconfig and don't have access to the button combo to achieve it, hold the bootsel button as you plug in the controller and use the 'force webconfig' uf2 file GP2040-CE supply.

Every page is being wiped and tidied as I get to step closer to reaching the ethos of this whole thing.


<img width="1600" height="1200" alt="ooiyhoj" src="https://github.com/user-attachments/assets/8da7b94f-431f-4a0f-b4e1-73602447878b" />

The big change here is that the additional key used as an additional 'up' is not combined with the up key on the PCB like the first one. It is currently set in the GP2040-CE firmware to also be 'up' but can also be changed there.

Among the many motivations way back when was seeing the madness of people's expectations of what to charge - many times charging as much or more than commercially available leverless. I charge 20 quid. Considering how cheap JLCPCB are you can afford to use some half decent key switches and colour match your key caps.

Firmware setup is very easy, but even better the restore file works on this one and you can find it above.

<img width="1600" height="1200" alt="i6i8ii7" src="https://github.com/user-attachments/assets/f492e3d4-74f4-4270-ad1f-2d8c1a30223c" />


You can buy cheap from OpenRhythmUK on Ebay (https://www.ebay.com/sch/i.html?_ssn=openrhythmuk) as usual. As much as the international shipping fee can be (realistically you still couldn't find cheaper) I am more than reasonable and a lot make contact about creating a bundle for them where not only do I discount everything, usually adding 2 or 3 more controllers doesn't change the shipping fee. I've given away a lot of bonus items for my own entertainment
