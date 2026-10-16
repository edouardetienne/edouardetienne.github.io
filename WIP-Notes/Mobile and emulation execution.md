# Mobile and emulation executiokn
How to test on different types of device configurations?

=> 3 tools:
- simulators
- emulators
- cloud device farms

## Simulators
- recreates the software environment of a device
- no reproduction of the hardware

## Emulator
- recreates the software environment of a device
- recreates the hardware environment
- still software-based approximations

MS Edge DevTools, but limited to Blink engine => during the development

## Cloud device farm
- thousands of real devices in secure data centers
- remote access via web browser
- test on actual devices1

ex: browserstack

=> system testing: check the app on actual devices

## Real devices
- UAT just before production to check critical user journeys