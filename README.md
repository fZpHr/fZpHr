# 42 student and R&D engineering apprentice at Renault.

## Exploitation and reverse

- [Override](https://github.com/fZpHr/override_42): ten setuid binaries,
  escalated with stack and heap overflows, format strings, GOT overwrite,
  ret2libc, shellcoding, and a `ptrace` anti-debug bypass. x86 32/64-bit.
- [Rainfall](https://github.com/fZpHr/rainfall_42): a second exploitation
  wargame (overflows, format strings, integer overflows, heap abuse) on 32-bit.
- [SnowCrash](https://github.com/fZpHr/snow-crash_42): Linux wargame covering
  SUID abuse, cron, pcap analysis and small-binary reversing.
- [Darkly](https://github.com/fZpHr/darkly_42): web-security wargame. Found and
  exploited the flaws of a deliberately vulnerable site: SQL injection, path
  traversal, request tampering / IDOR, brute force, weak cookie hashing, and
  open redirect.
- [CTF: La Quete du Stagiaire](https://github.com/fZpHr/CTF): a multi-stage CTF
  I designed and deployed end to end (web recon, SSH, privilege escalation via
  a sudoedit CVE, cleartext sniffing). Vulnerable services behind nginx,
  orchestrated with Docker Compose.

## Security tooling

- [Kintsugi](https://github.com/fZpHr/Kintsugi): a fork of Decompiler Explorer
  (dogbolt.org) on top of which I built the analysis layer. It runs several
  decompilers on a binary, then merges their output function by function with
  an LLM, keeping every line traceable to the decompiler it came from, and a
  second pass annotates the result and flags likely vulnerabilities. The work
  is the pipeline: multi-provider LLM integration, async jobs, token budgeting.
  Django + Docker. The decompiler understanding is the model's; the engineering
  around it is mine.

See [Cybersecurity](https://github.com/fZpHr/Cybersecurity) for the full index
and per-level writeups.

## Low-level and systems programming

- [kfs-1](https://github.com/fZpHr/kfs-1_42): a bootable x86 kernel written
  from scratch (multiboot, VGA text output, basic I/O). C and assembly.
- [libasm](https://github.com/fZpHr/libasm_42): a subset of the C standard
  library reimplemented in x86-64 assembly.
- [minishell](https://github.com/fZpHr/minishell_42): a Unix shell in C
  (parsing, pipes, redirections, environment expansion, signals, builtins).
- [ft_irc](https://github.com/fZpHr/ft_irc_42): an IRC server in C++
  (non-blocking sockets, multiple clients, channels, operators).

## Systems and infrastructure

- [Inception of Things](https://github.com/fZpHr/inception-of-things_42):
  K3s / K3d, Vagrant, GitOps.
- [cloud-1](https://github.com/fZpHr/cloud-1_42): Docker stack deployed with
  Ansible on a cloud instance.
- [BADASS](https://github.com/fZpHr/BADASS_42): BGP EVPN network simulated in
  GNS3 with FRRouting.
- [Windows / AD administration](https://github.com/fZpHr/PowerShell):
  Active Directory provisioning with PowerShell.

## Web

- [42insight](https://github.com/fZpHr/42insight): a platform centralizing
  tools and resources for 42 students (rankings, RNCP simulator, and more).

## Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=c,cpp,python,bash,linux,docker,kubernetes,nginx,django,postgres,git,ts&perline=12" alt="Stack" />
</p>

C / C++, x86 assembly, Python, Bash. Linux, Docker, Kubernetes, Ansible,
networking. Reverse engineering with Ghidra and gdb.
