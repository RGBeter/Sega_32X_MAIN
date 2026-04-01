# Sega_32X_MAIN
Reproduction of 32X MAIN based on official sega service documents and Cosam's Neptune work

This board has been dubbed "VA2" as that was the name sega called the planned 32X with integrated bodge capacitors

# Build Notes
These PCBs are tested to work with with a stock MARS SUB pcb, building these requires skills in microsoldering, QFP soldering, hot air rework, and Mega Drive/32X troubleshooting. It is highly recomendded you start with a set of known working parts from a donor 32X. This board is based off of a scanned VA1 32X PCB, but with built in bodge capacitors and resistors including C96, C97 and R66.

# BOM Notes
C96 and C97 should be omitted if you utilize a Gate Array 32x Interface chip (315-5818). If you utilize an SCA based 32X Interface chip (315-5818A) said capacitors should be 47pF when usiing 23MHz rated SH-2s and 100pF on 28MHz rated SH-2s.
