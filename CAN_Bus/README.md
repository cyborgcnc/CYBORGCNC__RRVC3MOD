<h1 align="center">CAN Bus Modifications and Info</h1>

In this section I will detail the modifications I did to use a CAN bus tool Head for the Vcore3, and will also post the way I modified the EVA catridge to mount everything.  The product that I used, is the Mellow/FLY SHT42 board.  THey have two versions, I chose the SHT42, but both are pretty much identical in functionality.  I have included therr STEP files, so feel free to modify as needed, if you need to make changes to the way I mounted mine.

As you can see, since I am running an enclosed chamber, I tried to design a mount that will also incorporate a fan, so that I can cool the 2209 driver that is on the
tool head.  Mellow provides also ALL the connectors, as well as a heatsink, that gets mounted on top of the 2209.  I have to say, their quality is really good, and they 
did a good job on this board (time will tell for sure)

The pictures below, along with a couple of renderings, should be very self explanatory, as to how it all fits together.  I am using dual blowers for mine, and hence this is the way I modified the back plate of EVA.  You will need to remix or make other modifications if you are using a different setup.  At this point, I am NOT planning on modifying any other EVA mounts.

I addition, you will also see, that I am using the UTOC-1 USB to CAN bus board from mellow.  This board basically plugs into the Rpi, and then gives a can0 port to the pi.  All communications on the CAN bus, then happen over this board.  If you only have ONE tool head, you can connect the SHT42 directly to the USB port, and then run a USB cable to the tool head (and separate 24V power).  Nothing wrong with doing this, and you will NOT need the UTOC board.  I have NOT tested this.  The only draw back to this, is you need to use a good shielded USB cable, and if in the future, lets us say, you need ANOTHER tool board, you will need to go back to CAN Bus and UTOC board.  I would strongly suggest you use 24V (and most use this) but your mileage will vary with 12v.  The SHT42 is rated to 9Amps total.  Plenty to run heaters and fans etc.  Again, POWER is POWER...do the math on what components you have and how much you need (the magic smoke will stay hidden).

<p align="left">
<img src="https://github.com/cyborgcnc/CYBORGCNC__RRVC3MOD/blob/main/CAN_Bus/CANBUS-1.jpg">
<img src="https://github.com/cyborgcnc/CYBORGCNC__RRVC3MOD/blob/main/CAN_Bus/CANBUS-2.jpg">
<img src="https://github.com/cyborgcnc/CYBORGCNC__RRVC3MOD/blob/main/CAN_Bus/CANBUS-3.jpg">
</p>
<p align="center">
<img src="https://github.com/cyborgcnc/CYBORGCNC__RRVC3MOD/blob/main/CAN_Bus/CANBUS-4.jpg">
<img src="https://github.com/cyborgcnc/CYBORGCNC__RRVC3MOD/blob/main/CAN_Bus/CANBUS-8.jpg">
<img src="https://github.com/cyborgcnc/CYBORGCNC__RRVC3MOD/blob/main/CAN_Bus/Render.new.1.jpg">
<img src="https://github.com/cyborgcnc/CYBORGCNC__RRVC3MOD/blob/main/CAN_Bus/Render.new.3.jpg">
</p>
