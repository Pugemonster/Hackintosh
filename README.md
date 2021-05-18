<img src="https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Logos/OpenCore_with_text_Small.png" width="200" height="48"/>

# Hackintosh
# Asus B85M-K OpenCore
ASUS B85-K motherboard.
- Full working OpenCore with Kexts and SSDTs

* OpenCore 0.7.0
* DSDT.aml
* SSDT-EC.aml
* SSDT-HPET.aml
* SSDT-PLUG.aml
* SSDT-USB-Reset.aml
* SSDT-SBUS-MCHC.aml
* SSDT-XOSI.aml

Working:
- Built in graphic (Intel HD Graphics 4400)
- Sound
- Ethernet
- USB
- Sleep
- CPU power management (Core i3 4170)
- IQSV
- iServices

Not working:
- None

## Hardware
| Item | Brand | Model | Driver | Comment |
|-----|-----|-----|-----|-----|
| Motherboard | ASUS | B85M-K | | |
| CPU | Intel | i3-4170 | | |
| RAM | Corsair | 2x4GB DDR3 1333 | | Overclocked to 1600 |
| iGPU | Intel | HD Graphics 4400 | built-in | Headless mode |
| dGPU | ASUS | RX 470 ROG 4GB | built-in | |
| Wireless | Atheros | AR9287 | HS80211 | |
| Ethernet | Realtek | RTL8111G | [RTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X/) | |
| Audio | Realtek | ALC887 | [AppleALC](https://github.com/acidanthera/AppleALC) | |
