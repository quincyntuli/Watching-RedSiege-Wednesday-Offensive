# Stephen Sims
#### stream date : 2022-Jan-19

## Who he is :
- Curriculum Lead at SANS Offensive Operations
- Curriculum Lead at SANS Advanced Exploit Development
- Curriculum Lead at SANS Cyber Defense Essentials
- Director Purple Team Operations Graduate Program 


### Social
[Youtube](https://www.youtube.com/watch?v=_hsSQKRsUmA&t=233s)<br>
[LinkedIN](https://www.linkedin.com/in/stephen-sims-2788091/)<br>
[Twitter ](https://twitter.com/Steph3nSims)<br>
<hr>


## Topic - 01 : Exploit Controls on Windows 10 /11

Exploit manipulation security controls in the past had been held back. With each successive Windows release, newer controls are being gradually turned on.

When Microsoft turns on security options, they get criticized for breaking legacy compatibility and when they don't they look insecure


### Exploit Mitigation and Security Controls

> - The [Enhanced Mitigation Experience Toolkit](https://support.microsoft.com/en-us/topic/emet-mitigations-guidelines-b529d543-2a81-7b5a-d529-84b30e1ecee0) was available for many years but had a very low adaption rate.
> - [Data Execution Prevention](https://docs.microsoft.com/en-us/windows/win32/memory/data-execution-prevention) has been available since Windows XP SP2 but was only turned on by default when Vista came out.
> - WIndows 10 came out with [Exploit Guard](https://www.microsoft.com/security/blog/2017/10/23/windows-defender-exploit-guard-reduce-the-attack-surface-against-next-generation-malware/) with most mitigation on by default.
 >- virtualization based security (VBS)
 >- Kernel running separately from main kernel
 >- Isolated user mod processes

### WIndows 11 Required Security Control

> - Many controls that were previously optional are now required
	> - Control-flow Enforcement Technology
	> - Hardware Stack Protection (Shadow Stack - no more 'smashing-the-sack')
	> - Reference to a paper called [R.I.P ROP](https://windows-internals.com/cet-on-windows/) by [Yarden Shair](https://www.linkedin.com/in/yarden-shafir-91a87957) and [Alex Ionescu](https://www.linkedin.com/in/aionescu/) , the end of return-oriented programming
	> - Application Guard
	> - Memory Integrity
	> - TPM 2.0
	> -  Secure Boot

## Topic - 02 : Patching

> - Delta patches to deal with 'DLL-Hell'
> - Hot-patching (function level patching) of live systems to avoid reboots


## Topic - 03 : Kernel  zero day weaponization certification

Stephen talked about "100% practical cert, that is the most advanced cert out there. " You will be expected to weaponize an intentionally vulnerbale windows kernel driver that has been created by SANS. It is a "brutal" exam where you are given only 5 hours to pass.






