!WORK IN PROGRESS, NOT YET READY FOR PRODUCTION!

# 240w-pd-powerbank
A 2-14S USB-C powerbank Hardware and Software Project, which is capable of charging and discharging at 48V@5A, which is the maximum power the USB-C PD 3.2 EPR standard supports.

The design is based on the BQ25756 4-Switch (bidirectional) Buck-Boost Charge-IC and the TPS26750 USB-C PD-Controller. Even though both of these Chips could work together standalone, the RP2354 MCU is used to control the PD-negotiation and Charger-Operation, to expand the functionality.

# Features

PCB:

- 100x80mm Board Size with 4x M3 Mounting Holes

- 6 Layer Board with sensitive signals on Layer 1 and 6

- 2oz outer copper and 1oz Inner Copper possible for improved thermal performance

Power:

- USB-PD EPR 3.2 Protocol with 48V/5A, PPS and AVS

- Dead-battery support (Powerup from 5V)

- BQ25756 4-Switch Buck-Boost Controller capable of bidirectional Buck/Boost

- 2S-14S battery support, recommended for 48V@5A PD EPR is 8S-14S (14S is most efficient)

- 5A input current through USB-C and 10A discharge current max from the battery

- LMR38010 Buck Converter that generates 3.3V from 4.2-58.8V

- 7V boost converter for Gate Drive Supply

Human-Machine Interface (HMI)
- SPI Header for one Display
- 2x Buttons and 1x Rotary Encoder for User Interface Navigation
- 1x Neopixel LED for Status Indication
- Buzzer for User Feedback and Alerting

# Cost

On JLCPCB the board itself costs about 100€/5 Pieces and the components are about 100€ per board. If you want to get the board assembled, the cost will be very high. The bulk of the cost comes from assembly because of the use of mostly non-basic parts.

# My Motivation:

My old powerbank broke a couple of months ago and I always wanted to make one myself. And I also noticed, that such an Product didn't yet exist on the market, so I decided to make the first.

