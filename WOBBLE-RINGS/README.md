# WOBBLE RINGS FOR VCORE3 PRINTERS

As you can see from the work here, I have created a set of “wobble rings” for the arms of the Vcore3.  This idea was originally posted by MirageC for his Hevort build.  
On his youtube video, he explains how he is able to source some very cheap ball screws, and make them better through the use of a system that allows them to 
freely move (if not dead straight).  As such, it eliminates print artifacts.  I thought this would be a good idea to use for the Vcore, and the leadscrews it uses. 
Ultimately, I would be looking for a belt driven Z, but at the moment, and due to the weight of the table, I put on the back burner.

Reason why I did this, was because I was getting small artifacts on my prints, and they were all measuring exactly 4mm apart, which pointed to screw wobble.
This is NOT to say you will have this problem!  In fact, the Vcore3 design is one that should ELIMINATE any sort of wobble, but if it shows up, it shows up.
Here is my fix here.

What you will need:

-You will have to print the Back-Arm, and then the Front Arms.  Bear in mind, that the Front arms are simply mirrors of each other.  
 So place the right one say in your slicer, mirror it, and you will have the left one.
 
-You will need to print the Rings.  These are comprised of Top Rings (you need three), Middle Rings (you need three) and Bottom Rings (you need three).

-Neodymium Magnets: 8mmx5mm (you will need 12)

-Steel pins: 3mm diameter x 8mm long (for the disks, you will need 48..I sourced these from McMaster Carr)

-Steel Pins: 3mm diameter x 35mm long (you can use the original ones that came with the kit).  These are for the arms, and where the ball end of the table rests ^ of them).

-Magnets for the Arms: Use the ones that came with the printer, in the original arms.

-TR8x4 Nut (can be anti-backlash if you want..3, one for each ball screw))

-Heat Inserts (To attach to the Arms, which is used for attaching the TOP Rings to the Arms). I used 4x5.5 M3..so the SHORT M3 Heat Inserts.

-4mm Steel Balls...you will need 12 (sourced from Amazon)

-3mm Screws, for attaching the top Ring, and the Arms to the Linear Bearings

-20x8mm Bearing for the front and Back support Brackets (Top bearings to support the lead screws and keep them from whipping)

The way you put these together is pretty self explanatory.

Just look at the pictures, and you will be able to see how they go together.  Basically, the Steel Balls sit between each of the Steel Pins in the disks, and they are held in place by the magnets on the other side.
PAY ATTENTION: to mount that magnets in a way that they ATTRACT each other, and NOT repel!

NOTE ON BACKLASH:  Since the steel balls sit between the steel pins this does two things.  It prevents any backlash, but in even more importantly, it allows the screw to spin, without the friction in the screw pushing the rings out of alignment.  What makes this possible is obviously the steel pins and balls, but also the WEIGHT of the table!  Even at a pretty fast Z axis homing routine, I never had an issue where the rings would go out of alignment.

ON SCREW ALIGNMENT:  Your lead screws would still need to be aligned with the rail and the stepper shaft!  These rings DO NOT change this requirement.  Reason for this is, that IF the screws are not aligned, and now they are free to move more, as the stepper turns, there is the potential of the screws whipping around!  This would cause them to wobble a lot, causing a lot of noise, and not a situation you want to be in.  A future improvement to this system would be to create a small bracket that would go over the linear rail on the top of each screw.  EDIT: I HAVE DESIGNED THIS BARCKET, and you can download it from ther files above.  The front is a mirror of each other, so print one, and then print a mirror for the left and right front led screws).  In this bracket, we would then fit a bearing, which would restrain (in a lose manner) the screw at the top.  This would allow one to have the screws not perfectly aligned, but still retain all the benefits of this system.  I am in the process of designing these brackets, and I will post them here as well shortly. EDIT: These are now posted here, labeled as Bed-Screw ALign brackets.

<p align="center">
<img src="https://github.com/cyborgcnc/CYBORGCNC__RRVC3MOD/blob/main/WOBBLE-RINGS/Back-Arm.JPG">
</p>
<p align="center">
<img src="https://github.com/cyborgcnc/CYBORGCNC__RRVC3MOD/blob/main/WOBBLE-RINGS/Front-Arms.JPG">
</p>
<p align="center">
<img src="https://github.com/cyborgcnc/CYBORGCNC__RRVC3MOD/blob/main/WOBBLE-RINGS/Steel-Bearing.JPG">
</p>
<p align="center">
<img src="https://github.com/cyborgcnc/CYBORGCNC__RRVC3MOD/blob/main/WOBBLE-RINGS/Back-Rings.jpg">
</p>
<p align="center">
<img src="https://github.com/cyborgcnc/CYBORGCNC__RRVC3MOD/blob/main/WOBBLE-RINGS/front-Rings.jpg">
</p>
<p align="center">
<img src="https://github.com/cyborgcnc/CYBORGCNC__RRVC3MOD/blob/main/WOBBLE-RINGS/FrontR-Arm.jpg">
</p>
</p>
<p align="center">
<img src="https://github.com/cyborgcnc/CYBORGCNC__RRVC3MOD/blob/main/WOBBLE-RINGS/Support-Beearing.JPG">
</p>


