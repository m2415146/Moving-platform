
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

There will be a link to  [Soldering first steps](https://github.com/m2415146/Soldering-first-steps- ) 

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

now you can check the operation of the system by controlling the program from your smartphone, which is written by  [Azamat Tavitov](https://github.com/m112521)



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


The control is performed using an application written by [Azamat Tavitov](https://github.com/m112521)



https://github.com/user-attachments/assets/3c18ef59-5599-45ed-93f8-bce452537a43  

## new variations of movement  

first, I need to print out the adapters from the motors to the wheels. since I do this at home, I will use the materials that I have  

3d printer - FlashhForge A5M  

the mode in the vegetable slicer, perhaps the standard setting for Petg Generic Flashforge, nozzle 04  

![Screenshot_126](https://github.com/user-attachments/assets/b0a96ac7-0640-4a09-b15d-b4ea3ec84c63)  

then I will try to print eSUN Petg on a filament.  

![photo_5357327998287733741_y](https://github.com/user-attachments/assets/4fcd0302-d572-45e0-86ab-a81a3a67363c)  

but I'm having trouble printing the eSUN again.  I will probably have to calibrate the filament. For now, I'll take an already working filament - Petg Geeetech  

Printing in action  



https://github.com/user-attachments/assets/f44fa785-e492-484f-85e3-be6618feb486



Ready parts  

![photo_5357436703909994633_y](https://github.com/user-attachments/assets/3fe8f319-a3c7-45f9-aa39-3b75b6dcc59c)  

I have printed 4 more samples and will be looking for new possibilities for modifying rotational motion that can be tested on our platform.

modelling a basic part for wheel  

I opened the file holderFootprint and made a 3d object out of it in the RhinoCeros program with screw holes. I have taken the thickness of 3 mm so far, as well as the plywood from which we cut the wheels in class. I will try the first layer with this thickness, then I will change it in accordance with the shape to be moved  

![Screenshot_129](https://github.com/user-attachments/assets/20bcddf2-58a4-487b-b2aa-51da94dbb573)  

## 1v of wheels  

the simplest version, it's just interesting to try. when I already put it on the seal, I thought that it was worth making the very area of contact with the surface longer.  

modelling in RhinoCeros. I slightly increased the thickness of the wheel itself to increase the area of contact with the surface , also trying to give strength to the wheel. I made holes that would include the caps from the tightening screws and at this stage realized that it was worth making the structure with the holders from the motors themselves monolithic. but I already have holders for the motors. perhaps I will also try to print the screws themselves - which will be in the form of bushings without threads and will be connected to the main part of the mower with glue

![Screenshot_130](https://github.com/user-attachments/assets/05023275-843f-4aca-9436-57b7fb923bc5)  

Slicing in OrcaSlicer. Same printer, same material, same settings.  

![Screenshot_131](https://github.com/user-attachments/assets/6437bba7-a91f-47af-aac7-c3749aa1b2a4)  

Printing in action  



https://github.com/user-attachments/assets/2ba48bd0-10f4-4e60-9bdc-1c9c61ac9585    

making a screws in RhinoCeros  

![Screenshot_132](https://github.com/user-attachments/assets/f39e968a-886d-4044-a898-5d6238f3ed3b)  

SLicing in Orcaslicer  

![Screenshot_133](https://github.com/user-attachments/assets/a2a26783-18d1-4852-b9cb-544418f32b0a)  

Same printer, material, settings. there is now video of printing because of low printing time  

there will be no photos of the result, since of the 3 printed screws, one was lost while I was removing it from the plate, the other had the screw cap broken off during removal, and the third, during an attempt to tighten, also broke - the cap broke off, and the rest of the screw had to be removed from the holes.  

I understood that the problem arises at the level of interlayer adhesion, but also because of the small size of the screw. therefore, I tried to arrange it differently on the printing platform and printed it again  

![Screenshot_134](https://github.com/user-attachments/assets/ad39f454-4f98-4b90-9007-707078eb9ca6)  

Same printer, material, settings.  

ready.  

![photo_5361940303537366981_y](https://github.com/user-attachments/assets/c58e2393-ea58-4bac-9690-32838bd52cf4)  



https://github.com/user-attachments/assets/886e0990-b502-4e0f-98a5-97c16a9197d7  

failure again. for now, I'll give up trying to print screws of a similar size.  

## 2v of wheels  

I find it interesting to move the rotation to another plane, so I started considering other options. I found a [gear project](https://www.printables.com/model/607786-bevel-gear-tester-with-parametric-gears)
gear project and decided to use it as a wheel.  

![Screenshot_140](https://github.com/user-attachments/assets/8d04267a-9705-4a61-94a3-ac4b0f65ba6f)  

in order to get the necessary parts from the project, I used the RhinoCeros program. Also there I added the motor element itself with spherical legs at an angle  

![Screenshot_137](https://github.com/user-attachments/assets/e274ef81-5419-4ec1-9e7c-654738af6f94)  

![Screenshot_138](https://github.com/user-attachments/assets/2cc98f0c-32c4-46ae-ab8e-8b6cb740d5e6)  

for the convenience of printing, I did not combine the models and used them for slicing OrcaSlicer  

![Screenshot_139](https://github.com/user-attachments/assets/c829f17f-c60a-417b-ae16-d4a49c8c8391)  

Same printer, material, settings












































































