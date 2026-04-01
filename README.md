# Sega_32X_MAIN
Reproduction of 32X MAIN based on official sega service documents and Cosam's Neptune work

This board has been dubbed "VA2" as that was the name sega called the planned 32X with integrated bodge capacitors

# Build Notes
These PCBs are tested to work with with a stock MARS SUB pcb, building these requires skills in microsoldering, QFP soldering, hot air rework, and Mega Drive/32X troubleshooting. It is highly recomendded you start with a set of known working parts from a donor 32X. This board is based off of a scanned VA1 32X PCB, but with built in bodge capacitors and resistors including C96, C97 and R66. RGBeter does not officially offer any debugging service or aid in building these PCBs.

In order to ensure reliability and no damage to mega drives this is installed in, you MUST order these PCBs with an edge bevel, and it is highly recomended that they recieve hard gold plating on said edge connector. When this is done, it may be difficult to solder to the 

# Bodge Instructions
32X bodge wires are POTENTIALLY eliminated with use of this PCB, however, knowledge of how YOUR 32X sub board is wired greatly dictates the required bodge wires, the following assumes you are using a STOCK 32X sub:

PHOTOS COMING SOON

1. Leave both the VCLK and AS jumpers OPEN
2. Install a wire between the AS point on the bottom of MAIN near the card edge, and the AS point on 32X SUB
3. Install a wire between the bodge resistor on C94 and the NON-Ground side of C53
4. Install a wire from Pin B13 of CN2 and pin 3 of IC15
5. Install a shielded wire from the top side of FB1 to the through hole labeled VCLK on SUB, with the shield soldered to a ground nearby

# BOM Notes
C96 and C97 should be omitted if you utilize a Gate Array 32x Interface chip (315-5818). If you utilize an SCA based 32X Interface chip (315-5818A) said capacitors should be 47pF when usiing 23MHz rated SH-2s and 100pF on 28MHz rated SH-2s.

# Special Thanks
Cosam, and all people involved in the Neptune project for both the inspiration, and the schematic drawings used in this project. Said schematics were modified to match a stock 32X.
