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

































