# Firmware, BIOS, and UEFI



This document explains firmware and the role of BIOS and UEFI in the computer boot process. These components are critical because they start the system before the operating system loads and can be targeted in advanced attacks.



---



## What Is Firmware



Firmware is low-level software stored on a chip inside hardware devices. It provides instructions that allow hardware to operate and communicate with the system.



Firmware exists in:

- Motherboards

- Routers

- Hard drives

- Network devices



Because firmware runs at a low level, it can be difficult to detect if compromised.



---



## What Is BIOS



BIOS (Basic Input/Output System) is older motherboard firmware that starts the computer when powered on.



Main functions:

- Performs hardware checks (POST – Power-On Self-Test)

- Detects connected devices

- Starts the boot process by loading the operating system



Limitations of BIOS:

- Limited security features

- Older interface

- Less flexible than UEFI



---



## What Is UEFI



UEFI (Unified Extensible Firmware Interface) is the modern replacement for BIOS.



Advantages over BIOS:

- Faster boot times

- Support for large drives

- Graphical interface

- Improved security features



UEFI is standard on most modern computers.



---



## The Boot Process (Simplified)



1. Power is turned on

2. Firmware (BIOS/UEFI) runs hardware checks

3. Firmware looks for a bootable device

4. The operating system loader is started

5. The OS takes control of the system



Understanding this process helps explain where low-level attacks can occur.



---



## Secure Boot



Secure Boot is a UEFI security feature that helps prevent unauthorized software from running during startup.



It works by:

- Verifying digital signatures of bootloaders

- Blocking untrusted or modified boot files



Secure Boot helps defend against:

- Bootkits

- Rootkits that load before the OS



---



## Security Relevance of Firmware



Firmware attacks are dangerous because:

- They occur before the operating system loads

- Traditional antivirus tools may not detect them

- They can survive OS reinstalls



Defenders should understand firmware to:

- Recognize boot-related threats

- Support incident response

- Ensure Secure Boot is enabled where appropriate



