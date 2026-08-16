# Building Guide for Philips CD-i 450 & 550

![Cover](./Pics/cover_450_550.jpg)

## Introduction

This variant fits the CD-i 450 & 550, since both share the same chassis and motherboard design. It utilizes a section of rear vents, and require two holes drilled on the bottom of the casing for installation. The final result is slick and does not require cutting additional holes or removing the Composite Video jack.

![Front View](./Pics/appearance_front.jpg)
![Bottom View](./Pics/appearance_bottom.jpg)
![Top View](./Pics/appearance_top.jpg)

Since the original Composite Video jack is preserved, it is possible to output both CVBS and RGBS at the same time.

![Dual Output 1](./Pics/dual_output_1.jpg)
![Dual Output 2](./Pics/dual_output_2.jpg)

## Parts

- 3D Printed parts - [STL Files](./3D%20Print)
- PCB - [Gerber File](./KiCAD/jlcpcb/gerber/CD-i%20450%20VGA%20Add-on.zip)
- VGA Port Slim, Female - [Link](https://github.com/jeffqchen/JeffParts/blob/main/Connectors/HD15/Slim/Female%20PCB/info.md)
- (Optional) Resistors, imperial 0603
  - R1: 0 Ohm, for fusing the 5V power line
  - R2: 1M Ohm, for connecting the VGA cable shielding to ground with ESD protection
- M2/M3 screw and hex nut - [Link](https://github.com/jeffqchen/JeffParts/blob/main/Parts/M2%20M3%20Hex%20Screw%20%26%20Nut/info.md)
  - 2x M3x8 screws
  - 2x M3x16 screws
  - 4x M3 nuts
- Colored wire at around 15cm

## Drilling The Chassis

![Drilling 1](./Pics/drill_1.jpg)

Assembly the 3D printed pieces together with screw and nuts, put it in place and use the two holes on the bottom as a guide to drill. The size of the bit should be 3mm / 1/8".

![Drilling 2](./Pics/drill_2.jpg)

Fit a piece of wood on the inside of the metal shielding for taking the pressure of the drill. Make sure to drill through both the plastic and the metal shielding.

After the holes are drilled, remove the 3D printed shell and disassemble it for the next step.

## PCB & Shell Assembly

There is nothing special about the soldering.

Resistor R1 and R2 are optional if you have requirements for 5V power or ESD consideration.

Make sure the VGA port is soldered on properly with no gap between the base of the port and the PCB.

![PCB Assembly 1](./Pics/pcb_1.jpg)

Use colored wires to help with later installation to your own discretion.

![PCB Assembly 2](./Pics/pcb_2.jpg)

Finally, install the PCB assembly into the 3D printed shell with M3x16mm screws and nuts.

## Installation

Thread the wires from the various vents into the metal shielding.

Note the first and last vent are used by the shell and should not have wires going through them. 

On the inside, I mainly used the top row holes since the lower ones might interfere with the motherboard.

Make sure the wires are not played with or bent too much during this step, as they tend to break at the solder joint.

![Installation 1](./Pics/install_01.jpg)
![Installation 2](./Pics/install_02.jpg)

After threading all the wires, carefully close the port assembly onto the back of the plastic chassis.

![Installation 3](./Pics/install_03.jpg)
![Installation 4](./Pics/install_04.jpg)

Insert two M3x8mm screws from the bottom of the console.

![Installation 5](./Pics/install_05.jpg)

Use two M3 nuts to secure the screws and the assembly.

![Installation 6](./Pics/install_06.jpg)

Before installing the motherboard back into the chassis, cut the 4 protruding capacitor leads from under the board to make sure they would not touch the newly installed nuts.

![Installation 7](./Pics/install_07.jpg)

Install the motherboard and make sure all the wires are accounted for.

![Installation 8](./Pics/install_08.jpg)

## Finalizing

Here is an example of my own RGB mod install. I trimmed the wires to better fit them on the inside of the console.

![RGB Installation](./Pics/rgb_install.jpg)

When closing the top metal shielding down, make sure to check if any wire is being crushed by the shielding (mine was fine.)

![Closing check](./Pics/closeup_check.jpg)


