# Junior Penetration Tester Notes

Practical study notes and command references for the [TryHackMe Junior
Penetration Tester (PT1) certification](https://tryhackme.com/certification/junior-penetration-tester/details).

The notes focus on the reconnaissance and privilege-escalation techniques
covered in the learning path. They are intended as a quick reference while
studying, not as a replacement for understanding the underlying concepts.

## Contents

- [Web enumeration](./web/enumeration.md) - port scanning, directory discovery,
  and virtual-host enumeration
- [Linux privilege escalation](./priv-escalation/linux.md) - system
  enumeration, logs, sudo, SUID, and kernel checks
- [Windows privilege escalation](./priv-escalation/windows.md) - credential
  discovery, PowerShell history, IIS, PuTTY, and common escalation checks
- [Active Directory enumeration](./AD/AD-enumeration.md) - host, SMB, LDAP,
  RPC, and domain enumeration
- [Authenticated AD enumeration](./AD/authenticated-enumeration.md) -
  Kerberos/AS-REP roasting and Windows account and privilege checks
- [Lateral movement and pivoting](./AD/lateral-and-pivoting.md) - remote
  services, scheduled tasks, and lab setup

## Responsible use

Use these commands only in TryHackMe rooms, systems you own, or environments
where you have explicit permission to test. The author is not responsible for
misuse of the material.
