<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg?v=72e30c58">
  <img alt="Jason Hunte: blue team and detection engineering. Security student at Seneca Polytechnic, Ontario, Canada." src="assets/banner-light.svg?v=3fbc96e7" width="100%">
</picture>

**I build detections, tune them until they're quiet, and write up what they catch.** Aiming at SOC and blue team roles. Best way to reach me: [LinkedIn](https://www.linkedin.com/in/jason-hunte-6546a2270/).

## Featured: [beacon-hunter](https://github.com/jhunte-sec/beacon-hunter)

Finds malware "phoning home" in network logs, explains every finding in plain English, and writes a one-file report you can attach to a ticket. Reads Zeek, Suricata, Sysmon, CSV exports and raw packet captures.

<a href="https://github.com/jhunte-sec/beacon-hunter">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/beacon-hunter-dark.png?v=78e20556">
  <img alt="beacon-hunter report on a real malware capture: 2 pairs worth a look, and a beacon map where the malware's two command servers stand out as solid timers" src="assets/beacon-hunter-light.png?v=c36aae26" width="100%">
</picture>
</a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/highlights-dark.svg?v=b24be929">
  <img alt="0.35 to 1.00 on Mirai botnet's real command channel; 9 of 9 conversations rebuilt from raw packets match Zeek's own log; 0 of 1,500 false alarms on simulated non-beacon traffic" src="assets/highlights-light.svg?v=15ffa717" width="100%">
</picture>

The [write-up](https://github.com/jhunte-sec/beacon-hunter/blob/main/docs/evaluation.md) covers what it misses, and a mistake I caught and corrected along the way.

## My detection lab

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/lab-dark.svg?v=be1db904">
  <img alt="Lab architecture: an outside attacker VM, a router and firewall between seven zones (DMZ edge, App, Internal, SOC, User, Admin, Remote), network taps from the SOC's IDS into the DMZ, App and Internal zones, and Wazuh agents on every host" src="assets/lab-light.svg?v=01e3df77" width="100%">
</picture>

Built for a network security course at Seneca, and run like a small company network: attacks come only from outside, through the DMZ, and every one has to show up as a specific alert someone can act on.

- **Detections tuned** in Wazuh, Zeek and Suricata so each attack raises one clear alert instead of a pile of noise
- **A triage queue and a weekly threat hunt**, so alerts get closed with a reason instead of ignored
- **Hardening, measured:** domain controllers taken from 28% to 92% on the CIS Level 1 benchmark, plus AppLocker and a three-tier PKI

> The lab itself stays private (it's coursework and holds credentials), but I'm glad to demo it or walk through any rule.

## Also

- **Incident response and forensics:** coursework in evidence collection, triage, and writing findings up the way a client report needs them
- **Up next: SOC-in-a-box**, a tool that takes a packet capture or Windows logs and turns them into a full case report

## Tools I use

**Detection and monitoring:** `Wazuh` · `Zeek` · `Suricata` · `Sysmon`<br>
**Windows and identity:** `Active Directory` · `Group Policy` · `PKI`<br>
**Code:** `Python` · `Bash` · `PowerShell`<br>
**Lab:** `VMware`
