# Hardware Security Considerations



## Why Hardware Matters in Cybersecurity

Hardware is the foundation of every system. If hardware is compromised,

software security controls can often be bypassed.



---



## Trusted Platform Module (TPM)

TPM is a hardware-based security component used to:

- Store cryptographic keys

- Support disk encryption (BitLocker)

- Enable Secure Boot



If TPM is compromised or absent, attackers may gain access to encrypted data.



---



## BIOS vs UEFI

UEFI improves security by supporting:

- Secure Boot

- Firmware integrity checks



Legacy BIOS systems are more vulnerable to bootkits and rootkits.



---



## Physical Attack Vectors

Physical access significantly increases risk. Common examples include:

- USB HID attacks (malicious keyboards)

- Hardware keyloggers

- Evil Maid attacks

- DMA attacks via Thunderbolt



Physical security is a critical but often overlooked control.



