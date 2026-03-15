![Name](https://img.shields.io/badge/Serial_No.-1-white?style=plastic)
<br>
![Name](https://img.shields.io/badge/Assy-312510-white?style=plastic)
![Name](https://img.shields.io/badge/Artwork-312513-white?style=plastic)
![Name](https://img.shields.io/badge/Revision-6A-white?style=plastic)
![Name](https://img.shields.io/badge/Video_format-PAL-white?style=plastic)


# Table of contents

<!-- TABLE OF CONTENTS -->
<details>
<summary>TOC - Click to enlarge</summary>
  <ul>
    <li>
      <a href="#starting-point">Starting point</a>
    </li>
    <li>
      <a href="#refurbishment-plan">Refurbishment plan</a>
    </li>
    <li>
      <a href="#initial-testing">Initial testing</a>
    </li>
    <li>
      <a href="#disassembly">Disassembly</a>
    </li>
    <li>
      <a href="#mainboard">Mainboard</a>
      <ul>
        <li>
          <a href="#visual-inspection">Visual inspection</a>
        </li>
        <li>
          <a href="#repair">Repair</a>
        </li>
      </ul>
    </li>
  </ul>
</details>


# Starting point

This Amiga 500 looks quite nice I think. It appears to be complete, and intact, from a mechanical point of view. It has obviously been opened previously as both warranty seals (on the underside and the rear) are broken. It is quite dirty - there is a significant amount of dirt and dust in the keyboard and the air grooves. There does not appear to be much corrosion on the metal shield and connectors on the rear.

There is a blend of screws used on the bottom cover: three torx and three Phillips. Also, there are no machine screws holding the internal floppy drive. My hunch is that this machine has been repaired (or tried repaired) previously.

Below are some pictures of the machine before refurbish (click to enlarge).

<p align="center">
    <img src="Images/Start06.jpeg" alt="Description" width="600">
    <img src="Images/Start05.jpeg" alt="Description" width="600">
    <img src="Images/Start04.jpeg" alt="Description" width="600">
    <img src="Images/Start03.jpeg" alt="Description" width="600">
    <img src="Images/Start02.jpeg" alt="Description" width="600">
    <img src="Images/Start01.jpeg" alt="Description" width="600">
</p>

There is something special interesting about this machine also: it´s serial number is #1. Of course, this is not a first Amiga of any kind. From some Google search I learned that Commodore used these #1 labels when machines were repaired/refurbished.

<p align="center">
    <img src="Images/Start07.jpeg" alt="Description" width="600">
</p>
<br>

# Refurbish activities

The planned refurbishment activites for this Amiga 500 (Order may vary. Several of them in parallell):

- [ ] Refurbish the casing
- [ ] Refurbish the keyboard
- [ ] Refurbish mainboard
- [ ] Testing and validation

The plan can be updated during the refurbishment process. Sometimes I discover areas that needs special attention.
<br>

# Initial testing

Before the refurbish commence, the Amiga 500 is connected to a TV set and powered on. This is to get an understanding of health of the machine. It is not meant as a complete test, but as an initial test.

The results are shown in the table below:

<div align="center">
  
| Test area | Test criteria | Result | Comment |
|:----------|:----------|:----------:|:----------|
| Boot up | ROM boot up screen is displayed | FAILED | Only green screen displayed |
| Floppy | Floppy drive is ticking | FAILED | No response from floppy drive | 
| LED | LED lights are lit correct | FAILED | Power light is flashing (~1s frequency)|

</div>

A video from the inital test: https://youtube.com/shorts/vrPpR4bFNvo

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)
<br>

# Disassembly

Disassembling the Amiga 500 is straightforward. First is to remove the six screws at the underside of the machine. But I notice that someone has been here before - there is a fine mix of torx and Phillips screw (three of each kind). Also, both the warranty seal on the rear (not visible in the picture below) and the seal seen in the picture are broken. In addition, the three machine screws holding the internal floppy drive are also missing.

<p align="center">
    <img src="Images/Dis01.jpeg" alt="Description" width="800">
</p>

With the six screws put of the way the machine is flipped back to upright position. Now the top cover is carefully pried off - note that there are two small plastic clips in the slit on each side of the covers. I recommend using a thin plastic spudger when releasing the small clips.

<p align="center" float="left">
    <img src="Images/Dis02.jpeg" alt="Description" width="600">
    <img src="Images/Dis03.jpeg" alt="Description" width="356">
</p>

The top cover is lifted away and the interior is exposed. Next action is to remove the keyboard. This is done by simply (carefully) pulling the 8-pin connector (of which only seven pins are used). **NOTE:** Take care to remember the original direction of the keyboard connector as this can be installed the wrong way when re-assembling.

<p align="center">
    <img src="Images/Dis04.jpeg" alt="Description" width="600">
    <img src="Images/Dis05.jpeg" alt="Description" width="600">
</p>

Wow! When the keyboard is removed the whole RF-shield is exposed. And what a view! It is not often I see RF-shields without any corrosion. This looks pristine. Also, it looks like the four metal tabs are intact - which is not that common. These are quite fragile and easily break.

<p align="center">
    <img src="Images/Dis06.jpeg" alt="Description" width="800">
</p>

The four torx head screws are removed (see wide arrows), the four metal tabs are folded to upright position (see small arrows) and the metal RF-shield is lifted from the mainboard. **NOTE:** When removing the RF-shield make sure to clean it properly soon after. The metal shield will easily start to corrode if there are fat/grease from human hands.

I notice something I have never seen before on an Amiga. There are four plastic "rods" sticking out from the RF-shield. I am not sure what the purpose of this, but with closer investigation it can seem like this is a support bracket to prevent the RF-shield from bending? The plastic bracket will sit between the `FAT AGNUS` chip and Data Path chip area.

<p align="center" float="left">
    <img src="Images/Dis07.jpeg" alt="Description" width="400">
    <img src="Images/Dis08.jpeg" alt="Description" width="460">
</p>

With the RF-shield removed the mainboard is exposed. And it looks to be in very good condition at first glance. There are some dust inside, but other than that it looks very nice. To remove the mainboard from the bottom cover the small plastic clip is pushed back. Note that these plastic clips are brittle so care must be taken to not break it. Also, the small screw holding the internal floppy drive is removed together with the two floppy drive connectors.

<p align="center">
    <img src="Images/Dis09.jpeg" alt="Description" width="800">
    <img src="Images/Dis10.jpeg" alt="Description" width="800">
</p>

The bottom cover and the bottom RF-shield also seem to be in fine condition too. There are some dust, but other than that I think this looks great.

<p align="center" float="left">
    <img src="Images/Dis11.jpeg" alt="Description" width="400">
    <img src="Images/Dis12.jpeg" alt="Description" width="431">
</p>

Notice that to remove the mainboard from the RF-shield all the 12 hex nut bolts (5mm ) needs to be removed.

<p align="center">
    <img src="Images/Dis13.jpeg" alt="Description" width="1000">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)
<br>

# Mainboard

This mainboard is the Assy 312510/Artwork 312513 Rev 6A. Well known for the Fat Agnus (8372A) capable of addressing 1 MB of Chip RAM.

## Visual inspection

The mainboard appears to be in very fine condition. I can not see any signs of either damage or repair. There is of course the normal amount of dust laying around on the mainboard, but that is to be expected after so many years. On the backside of the mainboard there are some flux residue, also on some individual pins. But I can not see any obvious signs of rework. I can not see any smoking gun why the mainboard should be faulty.

In the table below all the major custom IC found on the mainboard are listed. As can be seen from the table the custom MOS chips were produced during a time interval from week 51 in 1990 to week 24 in 1991. I think it is a fair guess that this Amiga 500 were manufactured sometime late summer or early autumn.

<div align="center">
  
| Chip/Area | Manufactor | Version | Date code | Socket | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| CPU | MOTOROLA | MC68000P8 | W51 Y1990 | Yes |  |
| KICKSTART | SHARP | 315093-02 | W04 Y1991 | Yes | Kickstart 1.3 |
| DENISE | CSG | 8362R8 | W16 Y1991 | Yes | |
| FAT AGNUS | CSG | 8372A 318069-02 | W17 Y1991 | Yes | 1MB / ECS |
| PAULA | CSG | 8364R7 | W24 Y1991 | Yes | |
| GARY | CSG | 5719 | W24 Y1991 | Yes | |
| ODD CIA | CSG | 8520 A-1 | W24 Y1991 | Yes | |
| EVEN CIA | CSG | 8520 A-1 | W24 Y1991 | Yes | |
| RAM | PANASONIC | MN41C4256-08 | W24 Y1991 | Yes | U16, U17, U18, U19|
| DATA PATH | NATIONAL SEMICONDUCTOR | MP9112<br>DM74LS373N | Unknown | No | U11, U13 |
| DATA PATH | NATIONAL SEMICONDUCTOR | MP9052<br>DM74LS244N | Unknown | No | U10, U12 |

</div>

Below are some pictures of the mainboard before repair and refurbish.

<p align="center">
    <img src="Images/Main01.jpeg" alt="Description" width="1000">
    <img src="Images/Main02.jpeg" alt="Description" width="1000">
</p>

## Repair

***What could cause this fault?***

The green colour shown on the screen do indicate that the machine is actually partly working: the Kickstart ROM and the CPU are apparently running as they detect a "RAM" fault. From the forum at LemonAmiga there is a great list of error colours found in the topic named [Amiga Error Colours, Blinks and Guru Codes](https://refurbished-commodore.com/amiga-error-codes):

> **Amiga Error Colours:**
>
> Green - There is an error in the Chip RAM or general Ram error

But does this mean that there is a RAM fault? Well, not necessarily. Even if the Kickstart ROM think that this is a RAM fault a bad chip or socket could also create this fault. A previous repair also had a green screen showing - it turned out that the PLCC socket holding the `FAT AGNUS` was causing the fault. Take a look here if you are interested: [Amiga 500 - Ser.No. 1420026](https://refurbished-commodore.com/a500-s-no-1420026)

***Reseating the socketed ICs***

It is not uncommon that an Amiga can fail just because some minor oxidation / corrosion in the socket, og the IC itself, have occured during several years. As good practice removing, an reseating, all socket chips is done.

It turns out that the ICs are really stuck in their sockets! I have to use plenty of contact cleaner on the pins, and great patience and care reseating these. For this process I reseat the ICs one-by-one and testing the machine for each reseated IC. After having reseated all ICs, except for the `FAT AGNUS` the machine still shows a green screen.

The `FAT AGNUS` is removed very carefully using a special PLCC extrator [(see the TOOLS section for details).](https://refurbished-commodore.com/tools). And holy moly, the `FAT AGNUS´ chip is really hard to remove. I have to use plenty of contact cleaner, patience and care to lift it out of the socket. Luckily, it lifted from the socket with only one slightly bent pin which is easy to align again.

<p align="center">
    <img src="Images/Main03.jpeg" alt="Description" width="600">
</p>

There are some signs of corrosion/oxidation on a few of the pins. But it is not too bad I think - I still think that the fault could be caused by a bad PLCC socket.

<p align="center" float="left">
    <img src="Images/Main04.jpeg" alt="Description" width="500">
    <img src="Images/Main05.jpeg" alt="Description" width="500">
</p>

***Replacing the PLCC socket***

There are 84 pins in the PLCC socket holding the `FAT AGNUS` chip so desoldering this is not trivial. Nevertheless, it is not complicated, but you need to be very careful to not rip or damage traces or pads. These are the steps I follow when desoldering the PLCC socket:

* Add fresh solder to all the 84 pins
* Pre-heating a large area of the PCB including and surrounding the PLCC pins with a hot air gun (with a very wide nozzle)
* With a desoldering gun remove 21 pins one side
* Repeat step 2-3 for the next 63 pins

Before trying to lift the socket from the PCB make sure that **ALL** the pins are free from solder. With some careful wiggling the PLCC will come off with almost no force. [A video showing how to check that the pins are free from solder](https://youtu.be/HKpMl6OLiYo).

<p align="center">
    <img src="Images/Main06.jpeg" alt="Description" width="600">
</p>

A brand new 84 pin PLCC socket is soldered in (and all 84 pins are checked for any short circuit), and the `FAT AGNUS` chip is put back in.

<p align="center" float="left">
    <img src="Images/Main07.jpeg" alt="Description" width="500">
    <img src="Images/Main08.jpeg" alt="Description" width="456">
</p

With the new PLCC socket installed the machine is powered on again. Will this fix the fault?

> **Result of repair attemt:**
>
> FAIL: Still the green screen. No change.

***Diagnostics with DiagROM***

There is a great tool for diagnosing the Amiga: [DiagROM](https://www.diagrom.com/). This ROM replaces the Kickstart ROM and give useful information even if the machine is barely working.

With the DiagROM installed the machine is powered on, and the result is a flickering red/green screen. [See video showing the result](https://youtube.com/shorts/zm5z15nACiE?feature=share).

According to the [DiagROM github page](https://github.com/ChuckyGang/DiagROM/blob/master/DiagRom%20Codes.txt) this should mean the following:

> ***Hardware problem***
> 
> Detected Chipmemerrors
> Green/Red

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)
<br>

