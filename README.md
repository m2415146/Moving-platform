# Moving-platform
Study task to make a moving platform  

## what we need to do  

![image](https://github.com/user-attachments/assets/4cdbc866-2583-4fa4-b30c-5100ff3820a2)  

![image](https://github.com/user-attachments/assets/1f9707b3-c7b8-4dfc-9aef-639c62460302)  

![image](https://github.com/user-attachments/assets/1185620e-b09a-4d51-82e7-01dd3f157313)  

## plan  

![image](https://github.com/user-attachments/assets/0d1998b3-3c4b-47ad-9d44-9f4fe546c8ff)  

## printing Mounting for wheels  

![image](https://github.com/user-attachments/assets/99fd69e9-7b81-42a0-af82-7516121e80e4)  

slicing in OrcaSlicer  

![image](https://github.com/user-attachments/assets/408967e6-3dec-4336-880f-09c5ad0a1541)  

This arrangement of the printing part at an angle is required in order to arrange the layers of the filament in order to better resist the load  

3d printer Creality Cr 10 SE, nozzle 0.4  

filament - PETg (Bestfilament)  

ready  

![image](https://github.com/user-attachments/assets/06d7c4f5-35fc-458c-b169-370212371d84)  

## Soldering  

There will be a link to Soldering project  

motor  

![image](https://github.com/user-attachments/assets/74ed58be-c2c8-4a4a-b8fa-170e8ce3c2bb)  

motor driver  

![image](https://github.com/user-attachments/assets/6d6086ee-b66e-4712-9fcd-ae273e7e0aa5)  

led stripe

![photo_5348459913023712523_y](https://github.com/user-attachments/assets/1f889f84-aed9-4bbf-b795-7ecb1db61dc1)  

the soldering points were covered with glue using a hot glue gun to protect them (since this was my first soldering and I had to be safe)  

![photo_5348459913023712530_y](https://github.com/user-attachments/assets/fcaa5970-10e5-49e2-a5f0-576ec9c71dbc)  

## we fix the wheel holder to the motor  

fixation takes place using screws and nuts with a rubber stopper M3. Tighten with a screwdriver (for the screw), holding the nut with tongs  

![photo_5348459913023712537_y](https://github.com/user-attachments/assets/95f96d5e-7332-47d3-bd06-610c23260feb)  

![photo_5348459913023712538_y](https://github.com/user-attachments/assets/c0277d01-49e9-4217-8c2c-4d233741ae52)  

check the fixation: the holder should not fall off from the motor  



https://github.com/user-attachments/assets/3da61deb-5c9a-44c5-a60f-2bdaaf4d3413  

result  

![photo_5348459913023712539_y](https://github.com/user-attachments/assets/b1597090-0d59-44cd-aeb4-a991f29a4119)  

it is important not to confuse the side from which the nut will stand, otherwise it will not be possible to achieve a good fixation  

also, a classmate showed a more effective way to tighten the screw and nut with a screwdriver and forceps  



https://github.com/user-attachments/assets/a5bcaa66-fdb9-4a56-b90c-fc863f89c91e  

## we strengthen the wires for the battery  

since the wire from the battery holder (battery) is weak enough, it was necessary to strengthen it with special metal adapters. one part of the adapter must fit on the rubber part of the wire, it must be bent with special forceps for better grip. then use soldering to connect  

![photo_5348459913023712560_y](https://github.com/user-attachments/assets/de8c638b-5c4f-40b2-8000-1a1536825e4f)  

then I took the thermal insulation tube, cut off the right part to cover the protruding part of the metal adapter. to make it compress the wire better, I used a construction hair dryer  

![photo_5348459913023712559_y](https://github.com/user-attachments/assets/10e14b68-2728-4f06-a759-e071f276e266)  

![photo_5348459913023712566_y](https://github.com/user-attachments/assets/4609885f-36ce-48cc-b617-d1e3470885a0)  

result  

![photo_5348459913023712560_y (1)](https://github.com/user-attachments/assets/893ac660-2a98-4f6e-9c6e-2bf159684a24)  

## assembly of electronic components  

We have connected the motors and the battery pack to the ESP32 board

![photo_5348459913023712610_y](https://github.com/user-attachments/assets/7e3d94fa-23c3-45c8-a89b-130a2fb0a463)  

5 volt battery to power the microcontroller 

![photo_5348459913023712611_y](https://github.com/user-attachments/assets/f9562d30-2bd5-4b57-b9b0-b343ab4cdd70)  

led stripe (there must have been some mistake here, perhaps at the soldering stage, since the strip did not work)  to port number 16  

![photo_5348459913023712612_y](https://github.com/user-attachments/assets/912e6a47-5539-4bda-baae-aea9051b620a)  

now you can check the operation of the system by controlling the program from your smartphone, which is written by Azamat Tavitov  



https://github.com/user-attachments/assets/2fefd0cb-a193-42c6-81dc-f85d08bf1cc4    

## Creating a platform and cutting a wheels  

since by this point I was already impatient to test the platform in action and was too lazy to go for measuring tools, I used lidar in my iphone using the roulette application  

I measured the width of the board and the finished 3rd class, which we were given in our hands 

![photo_5348459913023712676_y](https://github.com/user-attachments/assets/7dce85d7-98fa-4da0-aad4-d158816c6673)  

![photo_5348459913023712675_y](https://github.com/user-attachments/assets/44dcbf6a-6171-49b3-8744-afa4ada709f2)  

![photo_5348459913023712674_y](https://github.com/user-attachments/assets/a272d80b-6109-4e21-bed1-a26b70bb98d2)  

the platform and wheels had to be cut out of plywood 3 mm wide using a laser engraver  

I took the finished wheels file, removed the extra parts from it in RhinoCeros  

![photo_5348459913023712678_y](https://github.com/user-attachments/assets/ecf790c3-a7d0-474b-bf34-505b81e32f18)  

the size of the platform was modeled "by eye", as well as its simple shape was taken in order to quickly test the principle of movement in action  

the holes for the 3rd finished wheel were modeled "by eye" with a margin. fasteners for plastic ties were also modeled, with which the motors had to be fixed (the important point was that the structure should be able to be disassembled, without compromising the electronic ones  

![photo_5348459913023712685_y](https://github.com/user-attachments/assets/fe21e6a0-c6bb-48a3-861b-7620dbfa54a0)  

then I exported the file to the CorelDRAW program in the format.dxf and prepared for laser trimming. The lines were grouped so that the machine would first cut out the inner holes and only then the outer contours  

![photo_5348459913023712686_y](https://github.com/user-attachments/assets/00f9ec71-ee0a-4c95-9fca-e3dbfa96f6ef)  

laser cut in action  



https://github.com/user-attachments/assets/76141e67-dd14-4b72-9e3a-f2b1d9ca3f77  

result  

![photo_5348459913023712706_y](https://github.com/user-attachments/assets/8315288e-883e-4441-a8f3-f0de3e2132eb)  

## assembling components on the platform  

it was performed using plastic ties. black - wide, white - narrow  

motors with wheels are fixed on the underside of the platform  

![photo_5348459913023712713_y](https://github.com/user-attachments/assets/32977f0b-46de-4515-961d-26f4e077daa5)  

view from the upper side of the platform  

![photo_5348459913023712712_y](https://github.com/user-attachments/assets/a4e12296-b11e-4b47-96d1-9fd354b6b314)  

of course, it could have been made neater and more aesthetically pleasing. but the time of the lesson was coming to an end and I couldn't wait to see the work of the platform assembled so that next week I could continue to move further in my studies  

in order to secure the electronic components at the top of the platform, I used additional ties, which I placed crosswise  

![photo_5348459913023712715_y](https://github.com/user-attachments/assets/d3a4745e-b10a-46f3-af57-3836c7b99fef)  

we fix the electronic components by threading additional ties  

![photo_5348459913023712714_y](https://github.com/user-attachments/assets/93ed9065-3e12-4cbd-84f1-3a68ca4f655d)  

## wheel assembly  

the wheels were assembled using the black (outer) part of the rings, which we were provided with ready-made wheels that I cut out of plywood and fixed them to holders on motors that had previously been printed on a 3d printer. fixing took place with screws and nuts  

![photo_5348459913023712677_y](https://github.com/user-attachments/assets/5e5164e4-552c-46d4-9d93-17edde960da6)  

![photo_5348459913023712729_y](https://github.com/user-attachments/assets/c7a2ac3d-3e78-4528-95d5-80697a38d1cf)  

## checking the platform in motion 


The control is performed using an application written by Azamat Tavitov  



https://github.com/user-attachments/assets/3c18ef59-5599-45ed-93f8-bce452537a43





















































