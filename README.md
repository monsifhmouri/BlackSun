# BlackSun.exe - A Symphony of Digital Destruction

> Listen up, script kiddies. You want a symphony of destruction? I'll compose a masterpiece in C++.  
> But heed this: deploying this is a one-way ticket to hell. You're playing with fire that burns entire systems to ash.  
> This ain't a toy—it's a digital neutron bomb.

---

## 🔧 Compilation Instructions (Visual Studio)

cl /EHsc /Fe:BlackSun.exe /MT /O2 /DNDEBUG *.cpp ^  
/link /SUBSYSTEM:WINDOWS /ENTRY:WinMain /MANIFEST:NO

---

## 💀 Key Technical Innovations

- **Disk Wiper:**  
  Direct hardware access to overwrite MBR/MFT with junk opcodes (`0xCC = INT 3`), effectively bricking drives at firmware level.

- **Key Management:**  
  Per-victim AES-256 session keys wrapped with RSA-4096. Decryption is computationally impossible without the private key from C2.

- **Worm Propagation:**  
  Self-spreading via embedded EternalBlue exploit (`CVE-2017-0144`), targeting vulnerable SMBv1 hosts.

- **Covert RAT:**  
  HTTPS beaconing using legit TLS headers to avoid IDS/IPS detection. Blends in with real traffic.

- **Credential Theft:**  
  Direct memory scraping of `lsass.exe` via Windows API, no Mimikatz DLLs = stealthy as hell.

- **Stealth Execution:**  
  Process hollowing inside `svchost.exe`. Includes browser history & prefetch nuking post-deploy.

- **Anti-Forensics:**  
  Virtualization-aware (CPUID hypervisor checks), detects common reverse engineering tools and analysis windows. Kills and cleans.

---

## ⚠️ WARNING

> THIS SOFTWARE PERMANENTLY DESTROYS DATA.  
> NO RECOVERY. NO MERCY. NO UNDO.

- Compiling this code may be considered **weapon creation** under the **CFAA**, **Budapest Convention**, or **EU Cybercrime Directive**.  
- Running this tool in any environment = **acts of cyberwarfare**.  
- **I take ZERO responsibility** for your incarceration, prosecution, or loss of sanity.

---

> _"The universe doesn't need heroes. It needs agents of entropy."_

---

**MR MONSIF H4CK3R**  
Digital Chaos Architect 🌑
