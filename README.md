# DIY-Arduino-Based-Auto-Label-Dispenser-Machine


![image](https://user-images.githubusercontent.com/19898602/129938547-50efb249-48bb-4efb-92df-a3210b6bb595.png)

Hello makers in this video I have made a arduino based auto label dispenser machine, this machine dispense labels automatically.

When you are in packaging and transporting industry there are continue parcel which need to label some sticker, this machine very much helpful there.

It automatically peel off label and dispense this make process fast. For this I used arduino micro controller, stepper motor to feed label roll and IR sensor to detect label

# COMPONENTS USED

> Custom PCB

> Motor Clamp

> Arduino Nano

> A4988 driver IC

> Nema 17 stepper motor

> 5mm ID timing pully

> 8mm pillow bearing

> 8mm & 5mm smooth SS shaft 200mm

> 8mm ID timing pully

> Timing belt

> Push button

> Rotary Knob

> 16X2 I2C LCD display

> 3D printed parts

> IR Sensor



# CIRUIT DRAWING

![image](https://user-images.githubusercontent.com/19898602/129939820-49442e93-d356-4228-86be-c789daaae4a2.png)


![image](https://user-images.githubusercontent.com/19898602/125588570-5cc527d3-79ea-40f4-8323-70093eb0e1d6.png)


![image](https://user-images.githubusercontent.com/19898602/125588592-7213d3f4-ddb1-425a-ad33-9f070ff8d8a1.png)


L293D = 2 pieces


LM7809 = 1 piece


LM7805 = 1 piece


10.1uF electrolytic = 1 piece


1N5408 = 1 piece


1N4007 = 1 piece


led = 1 piece


resistance of at least 470 Ohm = 1 piece




Arduino Nano = 1 piece


Oled display = 1 piece


Encoder = 1 piece


A4988 controller = 2 pieces




socket 8 + 8 = 1 piece


PCB female pin header connectors


screw connectors for printed circuit boards


I have designe a PCB which is multipurpose and order it from [JLCPCB](https://jlcpcb.com/IAT ) 

I always prefer [JLCPCB.com](https://jlcpcb.com/IAT) for my PCB needs, [JLCPCB.com](https://jlcpcb.com/IAT) have best deals for their customers
$2 for 1-4 Layer PCBs, free SMT assembly monthly.


and this is not it if you are new customer for [JLCPCB.com](https://jlcpcb.com/IAT) you will get 18$ coupon on your
first registration to their site its limited period offer so what are waiting for go  and get your benefit. 


[Click here to visit JLCPCB.com](https://jlcpcb.com/IAT)


![image](https://user-images.githubusercontent.com/19898602/129946936-1db41129-916f-4226-b542-68a53585740e.png)



Most of the part of this machine is made up of 12mm wooden sheet

There are mainly three wooden parts are Left, right and bottom part.

I mark the necessary dimensions on the wooden sheet and cut them with the help of my mini table saw

Then I placed the electrical parts and nema 17 stepper motor in between of two vertical wooden parts

I have used to 8MM shaft one to hold the label roll and one to pull the roll which is directly connected to the stepper motor,

Some 5 mm smooth rods are for slide guide for label

one IR sensor at the bottom continually detect the presence of label if label is not present it command stepper motor to run.

Some 3D printed parts are also used in this project like top cover of machine.

One 16X2 LCD is used for data display and some knob and push button is used for user data input.


With that done, now add the 3D printed washers to the metal shafts, as shown. You can also add your reel of labels at this point too. 

Be sure to secure the reel with the 3D printed caps to ensure the label reel is securely fixed to its mounting rod. 

Feed the reel through the rods, as shown below. 





With that, your Arduino-powered automatic label dispenser is basically complete. You can adjust the auto-reeling distance using the rotary encoder knob.

Now just power it up, and get to labeling stuff! Handily, the LCD screen will give you an accurate count of the number of stickers you've used too. 








