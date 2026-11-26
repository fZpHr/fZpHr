# 42 student and R&D engineering apprentice at Renault.

## Exploitation and reverse

- [fuzzing-vr](https://github.com/fZpHr/fuzzing-vr): fuzzing C libraries with AFL++ and libFuzzer.
  Rediscovered CVE-2019-13288 (Xpdf stack exhaustion) and reproduced CVE-2018-6003
  (libtasn1 BER recursion) with custom harnesses and a structure-aware mutator.
- [Override](https://github.com/fZpHr/override_42): ten x86 32/64-bit binaries exploited from
  machine code only. Stack and heap overflows, format strings, GOT overwrite, ret2libc,
  shellcode, `ptrace` anti-debug bypass.
- [Rainfall](https://github.com/fZpHr/rainfall_42): fourteen more 32-bit binaries.
  Overflows, format strings, integer overflows, heap abuse.
- [SnowCrash](https://github.com/fZpHr/snow-crash_42): Linux wargame. SUID abuse, cron,
  pcap analysis, small-binary reversing.
- [Kintsugi](https://github.com/fZpHr/Kintsugi): reverse-engineering helper built on a fork of
  Decompiler Explorer. Runs several decompilers on a binary, merges their output function by
  function with an LLM while keeping each line traceable to its source, then annotates the
  result and flags likely vulnerabilities. Django, Docker, multi-provider LLM backends.

## Low-level programming

- [kfs-1](https://github.com/fZpHr/kfs-1_42): bootable x86 kernel written from scratch
  (multiboot, VGA text mode, basic I/O). C and assembly.
- [libasm](https://github.com/fZpHr/libasm_42): part of the C standard library in x86-64 assembly.
- [minishell](https://github.com/fZpHr/minishell_42): Unix shell in C.
- [ft_irc](https://github.com/fZpHr/ft_irc_42): IRC server in C++ with non-blocking sockets.

## Other security work

- [Darkly](https://github.com/fZpHr/darkly_42): web wargame (SQL injection, path traversal,
  IDOR, weak cookie hashing).
- [CTF: La Quête du Stagiaire](https://github.com/fZpHr/CTF): multi-stage CTF I designed and
  deployed (web recon, privilege escalation via a sudoedit CVE, cleartext sniffing). Docker Compose.
- [Cybersecurity Piscine](https://github.com/fZpHr/Piscine_Cybersecurity_42): six introductory
  projects (TOTP, ARP spoofing / MITM, Tor hidden service, basic reversing, crypto).

## Systems

- [Inception of Things](https://github.com/fZpHr/inception-of-things_42) (K3s, Vagrant, GitOps),
- [cloud-1](https://github.com/fZpHr/cloud-1_42) (Docker and Ansible),
- [PowerShell](https://github.com/fZpHr/PowerShell) (Active Directory provisioning).

## Web

- [42insight](https://github.com/fZpHr/42insight): a platform centralizing
  tools and resources for 42 students (rankings, RNCP simulator, and more).

## Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=c,cpp,python,bash,linux,docker,kubernetes,nginx,django,postgres,git,ts&perline=12" alt="Stack" />
</p>

