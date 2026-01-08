3D_dups2025_2025-12-24 (1).png
the bapzDUPone - very easy DIY, less than £8 all-in (if you're a fellow brit i've probably got 5+ spare of each controller project on hand to get rid of)


  >>> other GP2040-CE stuffs: Sound Voltex Pocket Zero >> Hand Pump (it up!) MX dubs >> Pop'n Music Pico >> Pop'n 1U Zero - even smaller but still very capable, in single board, single board choc low profile and dual layer LED 

WASD pad, with additional A to the right of the WASD (where some fight pads have jump). i wanted both not one or the other.
no turbo, no custom set ups, turn up and throw down.

tldr; upload gerber to pcb fab leave everything on default. silkscreen whatever colouur or just off. using the cheapest China shipping still arrived to the UK in just over a week, and somewhere like JLCPCB it's worth increasing the quantity to get more for the same money. 
a new customer on some services (like AllPCB) can get 20 of these PCBs and sent with FedEx on offer for about £2 all-in, play the game and show them some real business at some point too. 

GP2040-CE Firmware: use the RP2040 Zero (Waveshare) files from the GP2040 site - after flashing the key combo to reset in to web config mode is the far right bottom bottom with up and down. press and hold them [babonk, babank - windows disconnects/reconnects it] go to 192.168.7.1 in a browser. on the GPIO keys set up page there's an option at the bottom, pick that anbd press each key it asks and tell it to stop when you run out of buttons. Bit confusing as it says 's1, b1, etc etc' 

do as yer look - as per my label on the board i've done the same RT-LT layout as all fight controllers i've had, it just made sense to keep it familiar. you do you though:

hit save, hit restart, then your key combo for web config is start-x-y from this point on. if you do edit the pcb keep this in mind that gp01,10 and 11 is that combo

PCB files? my files are a mess and may get sorted, and schools using chromebooks and online services makes things interesting. Kicad's Gerber viewer can send to PCB editor - a common edit would likely be the silkscreen - Kicad will let you import a dxf in the PCB editor but if that's already a bit confusing use EasyEda online, import your image and set it to top or bottom silkscreen layer as required. ... it's 15 switches with a via near the zero for the extra up. thanks to projects like GP2040-CE these things are all possible with barely any effort.

i did however put quite a lot of time testing layouts as most other designs i found online made my wrists or fingers sore quite quickly and i am getting old, or possibly a worse crime, would spend good money on doing the job right then 3D print some tat to put on their lovely work. i tested low profile keys. and over did it with some LED versions. a lot of decisions made. at the very least there should be a plastic plate that sits on top of the PCB. we didn't even finish the handful of these in use, soldering them up to test they've stayed like this and no one cares as they function well for the purpose. i would like to figure out how to cut the stalk sleeve inside the cap as currently there's approx 5mm above the stalk, if the stalk reached the top of the sleeve the cap itself would sit that bit lower. the single pcb is perfectly solid enough.



<img width="2160" height="1308" alt="3D_dups2025_2025-12-23" src="https://github.com/user-attachments/assets/24a744e5-4899-4750-8dab-e0b22f853927" />


-----
the waffle, and potentially useful points

over the long summer break i decided to put some time in to being ready to show the youth how it's done, randomly trying out leverless for the first time and very quickly mad much more expensive devices useless. eventually i hit a wall needing to throw a quarter or half circle on the d-pad just wasn't happening and despite tolerating it for quite a while i just couldn't get much further - i immediately progressed once i took delivery of these pcbs.
i had a lot of Gateron Milky MX style keys that were taking up space, bags of 1U keycaps to get rid of, excess supply of Pico's and RP2040 zero's as making use of Ali Express and buying multiples ends up costing a quarter of the price of ordering singles locally.

this happened to make a good project starter and after introducing the students to marvel vs capcom 2 on the dreamcast a few years ago i knew i had something that could work
------

there's no drill holes/plate/case? uwotm8

i don't like 3D printing for a final piece on the whole anyway, there are a number of DIY looking devices on AliExpress that reassures me it's best avoided. other projects that will be up here at some point do use plates (a pcb with cut outs for the keys)
any option can be added pretty quickly for your own design, but they keys i had ot use up were 5pn which unlike 3 pin i consider to be PCB mount. having tried it they are perfectly sturdy.

3D printing is just an absolute no-go during the school day for the running time and noise alone although being able to allow creative time to utilise such tech would be great, it's just not going to happen

most of my bought devices use a plastic plate which would add to the design and could secure the keys, the CNC/laser i ordered second hand got damaged being sent to me and i realised really cutting away at plastic isn't particularly good so i settled on 3D printing a mould which i would then cast clear resin plates. the mould goes up to the point shown in pics, easily achieved in most 3d printing apps with use of a mould mode, negative mode, set the item within a larger shape and select 'hole' in something like tinkercad.

the GPIO i chose was in part to leave available plenty of easy options for the students to customise, stick in tactile switches etc. but personally I've never used any of the other keys and they've never worked for me anyway due to my OS set up. the most likely addition for students would be a bunch of LEDs added straight from a strip and set in to whatever case set up they decide on.

<images and stuff here soon>

using the template personalising and playing at design can be made a task that fits in to lesson time and printed out. that gets places on the pcb, the resin sheet goes on top, and fitting the keys secures the resin sheet and the design in place. badabing.

no hotswap, not really any point adding to the cost for that.
