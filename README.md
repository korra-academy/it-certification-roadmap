# IT Certification Roadmap — Which Cert, In What Order

A free, vendor-neutral **IT certification roadmap**: which certification to take first, what each one is actually for, realistic study hours, and the order that builds a career instead of a wall of PDFs.

Maintained by [Korra Academy](https://korra.academy/) — the team behind **[Korra.Training](https://korra.training/)**, live certification prep with human instructors.

## The short answer

- **Brand new to IT** → CompTIA **A+** (or go straight to Network+ if you already build PCs / run a home network).
- **Into networking** → **Network+** → Cisco **CCNA**.
- **Into cyber security** → Network+ → **Security+** → then hands-on (CyberOps, eJPT, or a SOC role) before anything expensive.
- **Into cloud** → **AZ-900** or **AWS Cloud Practitioner** (fundamentals) → **AZ-104** or **AWS Solutions Architect Associate**.
- **Already 3–5 years in security** → CISSP territory. Not before — it's a management-track exam with an experience requirement.

## The map

```
            START
              │
   ┌──────────┴─────────┐
   │  No IT experience  │        Some IT / helpdesk experience
   │  CompTIA A+        │───────────────┐
   └──────────┬─────────┘               │
              ▼                         ▼
        CompTIA Network+  ◄─────  (skip A+ if confident)
              │
   ┌──────────┼──────────────────┐
   ▼          ▼                  ▼
 CCNA     Security+         AZ-900 / AWS CP
(network) (cyber entry)     (cloud fundamentals)
   │          │                  │
   ▼          ▼                  ▼
 CCNP     hands-on labs,     AZ-104 / AWS SAA
          SOC/blue-team,         │
          eJPT/CySA+             ▼
              │             specialise (security,
              ▼             DevOps, data)
          CISSP (after ~5 yrs experience)
```

## Realistic study budgets

| Certification | Typical study time (working adult) | Notes |
|---|---|---|
| CompTIA A+ | 8–12 weeks (2 exams) | Broad basics: hardware, OS, troubleshooting |
| Network+ | 6–10 weeks | The single highest-leverage foundation cert |
| Security+ | 6–10 weeks | HR-filter cert for entry cyber & many gov roles |
| CCNA | 10–16 weeks | Labs matter more than videos (Packet Tracer is free) |
| Linux+ | 8–12 weeks | Live in a Linux VM daily; the exam rewards muscle memory |
| CySA+ | 8–12 weeks | Blue-team analyst cert; log reading and triage, not theory |
| AZ-900 / AWS CP | 2–4 weeks | Fundamentals; fine as a first-ever cert for cloud-curious |
| AZ-104 / AWS SAA | 8–12 weeks | Do real console labs; question dumps teach you nothing |
| CISSP | 12–20 weeks | Requires ~5 yrs paid experience for full status |

Rule of thumb: **1 hour of hands-on lab per hour of video/reading.** Certs without labs evaporate in interviews.

## Cert profile: CompTIA Linux+

**Where it fits:** after Network+, on the way to cloud, DevOps, or security roles — anywhere the terminal is your day job. Most servers, containers, and cloud instances run Linux, so this is the quiet prerequisite behind half the map above.

**What it actually tests:** managing a Linux system for real — users and permissions, services, storage, networking from the command line, shell scripting, and increasingly containers and Git. It's a doing exam, not a memorising exam.

**How to prepare:** install Linux somewhere you'll touch it every day (an old laptop, a VirtualBox VM, or WSL on Windows — all free). Do every task from the terminal, break things, fix them from the logs. A course alone won't build the muscle memory the exam checks for.

**Worth knowing:** LPIC-1 covers similar ground across two exams and employers treat the two roughly equally. Either badge works; the fluency behind it is what interviews test.

## Cert profile: CompTIA CySA+

**Where it fits:** after Security+, once you've spent time in a SOC, helpdesk-with-security-duties, or a serious homelab. It's the "I can actually do the job" step between the entry badge and the expensive management-track exams. CompTIA suggests a few years of hands-on experience; there's no hard prerequisite, but the exam assumes you already think like an analyst.

**What it actually tests:** the day-to-day of a security analyst — reading logs and alerts, spotting what's noise and what isn't, vulnerability management, incident response steps, and writing up findings for people who weren't there. Expect performance-based questions where you're handed output from a tool and asked what it means and what to do next.

**How to prepare:** build a small detection lab — one Linux VM shipping logs to a free SIEM (Wazuh or Security Onion), one deliberately noisy target. Generate traffic, scan it, break it, then find the evidence in the logs. Learn to read Nmap, Wireshark, and vulnerability-scanner output cold. Keep a notebook of every alert you investigated and what the answer turned out to be; that notebook is your interview portfolio too.

**Worth knowing:** CySA+ is defensive — it's the blue-team counterpart to hands-on offensive certs like eJPT. If you want to pentest, go that way instead; if you want a SOC analyst or threat-hunting role, this is the one hiring managers recognise. Like Security+, it expires after three years unless you renew with continuing-education credits.

## How to study for any of them

1. One primary video course or book — finish it, don't collect five.
2. Labs alongside every module (Packet Tracer, a cloud free tier, an old laptop with Linux).
3. Spaced flashcards for ports, acronyms, models.
4. Two full timed practice exams before booking; book when you clear ~85%.
5. A study group or instructor for the parts that won't stick — that accountability is exactly what we run at [korra.training](https://korra.training/).

## FAQ

**Which IT certification should I get first?**
CompTIA A+ if you're completely new; Network+ if you already troubleshoot your own network comfortably. Everything else stacks on those.

**Are IT certifications worth it without a degree?**
Yes — for entry roles (helpdesk, NOC, SOC) certs + a homelab are the standard no-degree route. Past mid-level, experience outweighs both.

**Can I go straight to Security+ / straight into cyber?**
You *can* pass it cold, but you'll interview badly. Networking fundamentals first is the difference between knowing the answer and understanding it.

**Certs or projects?**
Both: certs open HR doors, a documented homelab (see our GitHub profile for more starters) wins the conversation behind the door.

---

### About Korra Academy

[Korra Academy](https://korra.academy/) runs live online training across eight doors: [Kids](https://korra.kids/), [Study](https://korra.study/), [Career](https://korra.career/), [Business](https://korra.business/), [Tutor](https://korra.one/), [Training](https://korra.training/), [Bot](https://korra.bot/) and [Codes](https://korra.codes/). Preparing for one of these exams with a real instructor beats grinding alone — start at [korra.training](https://korra.training/). MIT licensed.
