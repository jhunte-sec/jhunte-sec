# Jason Hunte

**Security student working both sides: I attack in labs to learn what defenders have to catch, then build and tune the detections that catch it.**

I'm aiming at SOC and blue team work, with enough offensive practice to know what an alert looks like from the other side.

- Studying at Seneca Polytechnic
- Most of my time goes into detection: SIEM rules, IDS tuning, and cutting false positives
- On the offensive side I work through TryHackMe boxes and my own lab
- Best way to reach me: [LinkedIn](https://www.linkedin.com/in/jason-hunte-6546a2270/)

---

## Blue team

### Enterprise detection lab (course project)
A multi-VM Windows and Active Directory network with a full monitoring stack, built for a network security course at Seneca.

- **Sensors and SIEM:** Zeek, Suricata with ET Open rules, and Wazuh, with custom detection rules tuned for the lab
- **Hardening:** brought the domain controllers to a CIS Level 1 baseline and measured the before and after
- **The standard I held it to:** one attack should raise one specific alert, not a wall of noise. Getting there was most of the work.
- **Triage:** a scripted triage queue and a weekly threat hunt, so alerts get closed with a reason instead of ignored

> The lab itself stays private (it's coursework and holds credentials), but I'm glad to demo it or walk through any rule.

### Incident response and forensics
Coursework in digital forensics and incident response: evidence collection, triage, and writing findings up the way a client report needs them.

---

## Red team

### ctf-mcp (private for now)
A tool server I built for authorized CTF practice. It gives an assistant a small set of recon tools, and the part I care about most is the guardrails: nothing is in scope until a person sets one target, and anything beyond reconnaissance stays locked until a person arms it. Every action is logged.

> Happy to demo it. I'll publish it once it's cleaned up.

---

## Tools I use

`Wazuh` · `Zeek` · `Suricata` · `Active Directory` · `nmap` · `Python` · `Bash` · `PowerShell` · `VMware`

---

*Open to junior SOC and blue team roles.*
