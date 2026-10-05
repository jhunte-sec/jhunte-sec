# Jason Hunte

**Security student focused on blue team work: I build detections, tune them until they're quiet, and write up what they catch.**

I'm aiming at SOC and blue team roles.

- Studying at Seneca Polytechnic
- Most of my time goes into detection: SIEM rules, IDS tuning, and cutting false positives
- Best way to reach me: [LinkedIn](https://www.linkedin.com/in/jason-hunte-6546a2270/)

---

## Projects

### [beacon-hunter](https://github.com/jhunte-sec/beacon-hunter)
Finds malware "phoning home" in network logs and explains every finding in plain English, with a one-file HTML report for the ticket. Reads Zeek, Suricata, Sysmon, CSV exports and raw packet captures.

The standard way to spot a beacon is to check whether the gaps between connections are regular. Real implants break that: they miss check-ins, and when their command server is dead, the operating system's retries scramble the timing in the logs. beacon-hunter handles both. On real malware traffic from the IoT-23 dataset, it turned two C2 channels that scored 0.35 and 0.65 under the standard method into clear 1.00 timers, without adding a single false positive across 1,500 simulated non-beacon samples. The write-up covers what it misses, and a mistake I caught and corrected along the way.

`Python` · `Zeek` · `Suricata` · `Sysmon` · `pcap` · evaluated on labeled malware captures

---

## What I work on

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

## Tools I use

`Wazuh` · `Zeek` · `Suricata` · `Active Directory` · `Python` · `Bash` · `PowerShell` · `VMware`

---

*Open to junior SOC and blue team roles.*
