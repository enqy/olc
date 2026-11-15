# olc: an overloaded type-c

**Current Version:** 0.1.0

## common

CC1/CC2: used for orientation detection (5.1k pulldown to ground)
GNS: ground

## normal

VBUS: vbus

other pins used for whatever is needed

## chip/som debug

VBUS: reset
SBU1/SBU2: swd or equivalent 2 wire debug
D1/D2: debug usb 2.0, either to onboard debugger or to som debug usb
SSRX1+/SSTX1+: debug uart
SSRX2+/SSTX2+: reserved for future use
SSRX1-/SSTX1-/SSRX2-/SSTX2-: ground

# olc-2

A 2 port spec combining a normal port and a debug port.

Normal port on left, debug on right, spaced 16mm apart center to center.
