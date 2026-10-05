<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg?v=72e30c58">
  <img alt="Jason Hunte: blue team and detection engineering. Security student at Seneca Polytechnic, Ontario, Canada." src="assets/banner-light.svg?v=3fbc96e7" width="100%">
</picture>

**I build detections, tune them until they're quiet, and write up what they catch.** Aiming at SOC and blue team roles. Best way to reach me: [LinkedIn](https://www.linkedin.com/in/jhunte-sec/).

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
  <source media="(prefers-color-scheme: dark)" srcset="assets/lab-dark.svg?v=032ce7ea">
  <img alt="Lab architecture: an outside attacker VM, a router and firewall between seven zones (DMZ edge, App, Internal, SOC, User, Admin, Remote), network taps from the SOC's IDS into the DMZ, App and Internal zones, and Wazuh agents on every host" src="assets/lab-light.svg?v=1eff5c68" width="100%">
</picture>

Built for a network security course at Seneca. Attacks come only from outside, through the DMZ, and every one has to show up as a specific alert someone can act on.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/lab-tiles-dark.svg?v=91722bf2">
  <img alt="Detections tuned in Wazuh, Zeek and Suricata so each attack raises one specific alert; a triage queue and a weekly threat hunt; domain controllers taken from 28% to 92% on the CIS Level 1 benchmark, plus AppLocker and a three-tier PKI" src="assets/lab-tiles-light.svg?v=a3749937" width="100%">
</picture>

> The lab itself stays private (it's coursework and holds credentials), but I'm glad to demo it or walk through any rule.

## Also

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/also-dark.svg?v=f72c8e3b">
  <img alt="Incident response and forensics coursework: evidence collection, triage, and client-ready findings. SOC-in-a-box, in progress: drop in a packet capture or Windows logs and get a full incident case report" src="assets/also-light.svg?v=9c2f787f" width="100%">
</picture>

## Tools I use

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/toolbox-dark.svg?v=13404eae">
  <img alt="Detection and monitoring: Wazuh, Zeek, Suricata, Sysmon. Windows and identity: Active Directory, Group Policy, PKI. Code: Python, Bash, PowerShell. Lab: VMware, Windows Server, Ubuntu, WireGuard" src="assets/toolbox-light.svg?v=8b38a6cf" width="100%">
</picture>

<a href="https://www.linkedin.com/in/jhunte-sec/">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/cta-dark.svg?v=65c9fc42">
  <img alt="Open to junior SOC and blue team roles. Connect on LinkedIn" src="assets/cta-light.svg?v=e3886420" width="100%">
</picture>
</a>
