# HackerLab Benin 2026 — Writeups

Writeups pour le CTF **HackerLab Benin 2026** (flag format `HLB2026{...}`).

## Par CTF multi-épreuves

### Forensics — The Fall of JANUS
- [Q1 · Ransomless (100 pts)](./janus/01-ransomless.md) — reversing ransomware BURNOUT (XTEA-CTR)
- [Q2 · The Trojan Horse (100 pts)](./janus/02-trojan-horse.md) — triage webshell + logs Apache
- [Q3 · New Blood (100 pts)](./janus/03-new-blood.md) — SAM + TS logs
- [Q4 · Royal Heist (100 pts)](./janus/04-royal-heist.md) — prefetch + PowerShell history
- [Q5 · No Witnesses (100 pts)](./janus/05-no-witnesses.md) — USN journal
- [Q8 · True Identity (100 pts)](./janus/08-true-identity.md) — OSINT sur `feu.hackerlab.bj`
- [Q9 · Hidden Treasure (100 pts)](./janus/09-hidden-treasure.md) — stego base64 inversé

### Web — Last Departure (Northline)
- [Q4 · WINDOW (30 pts)](./northline/04-window.md) — SSRF + decimal IP bypass

### Misc — BATMAN (HARMATTAN)
- [Q1 · Operation BATMAN (500 pts)](./harmattan/01-operation-batman.md) — enquête OSINT 28 Q + 3 puzzles

### Misc — The Fall of Memento
- [Q1 · Under Seal (200 pts)](./memento/01-under-seal.md) — PDF417 + AES-256
- [Q2 · Shooting window (100 pts)](./memento/02-shooting-window.md)
- [Q3 · The Hideout (50 pts)](./memento/03-hideout.md)

### EB.ICS — Sail Away
- [Q2 · Flow in (150 pts)](./sail-away/02-flow-in.md) — XXE sur import RTZ
- [Q3 · Welcome to the Machine (100 pts)](./sail-away/03-welcome.md) — AES-256 reverse creds
- [Q4 · Renegade (100 pts)](./sail-away/04-renegade.md) — Modbus TCP write

### Misc — Kiss of Death
- [Q6 · Papyrus (300 pts)](./kiss-of-death/06-papyrus.md) — angecryption 3 étapes

### AD/Pentest — FBI Valdoria
- [Q11 · Deep Archive (100 pts)](./fbi-ad/11-deep-archive.md) — Constrained Delegation S4U
- [Q12 · Core Systems (100 pts)](./fbi-ad/12-core-systems.md) — RBCD + MachineAccountQuota

## Par catégorie

### Crypto
- [vault0037](./crypto/vault0037.md)
- [lockbox](./crypto/lockbox.md)
- [inside-job2](./crypto/inside-job2.md)

### PWN
- [vault-keyctl](./pwn/vault-keyctl.md)

### Web
- [stay_behind](./web/stay_behind.md)
- [inside-job1](./web/inside-job1.md)
- [hl-deathmatch-battle01](./web/hl-deathmatch-battle01.md)
- [broker](./web/broker.md)
- [cagliostro](./web/cagliostro.md)

### Active Directory
- [sealed-order-q11](./ad/sealed-order-q11.md)
- [core-systems-q12](./ad/core-systems-q12.md)
- [subject-file](./ad/subject-file.md)

### Misc
- [human-after-all](./misc/human-after-all.md)
- [inside-job3](./misc/inside-job3.md)

### Forensics
- [hl-broken-relay](./forensics/hl-broken-relay.md)
- [forensic-recovery](./forensics/forensic-recovery.md)
- [cashcache](./forensics/cashcache.md)

---

> Tooling : impacket, pymodbus, pyzbar/pdf417decoder, pycryptodome, outils AD classiques (getTGT, getST, smbclient…).
