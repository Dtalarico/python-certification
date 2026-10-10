# Python Certification — Infrastructure Automation Track

## Why this repository exists

This is my dedicated Python learning and certification record. My primary professional direction is **Linux systems and cloud infrastructure engineering**, with three connected disciplines: **Red Hat, Python, and Microsoft Azure**.

Python is not a replacement for Linux administration. I want to understand enough Python to **write, read, debug, and maintain the automation I use**, rather than copying scripts I cannot explain.

My larger practical laboratory is [Baby Cloud](https://github.com/Dtalarico/baby-cloud): a planned four-node initial Raspberry Pi build growing toward an eight-node Beowulf-style system, with potential Radio Free Redoubt and DX League workloads.

## Credential roadmap — names worth remembering

| Order | Credential | Full name | Learning target |
| --- | --- | --- | --- |
| 1 | **PCEP** | Certified Entry-Level Python Programmer | Variables, data types, expressions, conditionals, loops, functions |
| 2 | **PCAP** | Certified Associate Python Programmer | Modules, exceptions, strings, object-oriented programming, broader language fluency |
| 3 | **PCPP1** | Certified Professional Python Programmer Level 1 | Deeper Python design, programming practices, and practical application |

These are **Python Institute / OpenEDG** credentials, **not Python Software Foundation certifications**. The credential plan is a goal, not a claim that any exam has been scheduled or passed. Verify live exam requirements before registering.

Official certification track: https://pythoninstitute.org/certification-tracks

## How this relates to Red Hat and Azure

- **Red Hat:** Systems administration first, then automation and higher-level engineering. Linux and RHCSA study remain their own track.
- **Python:** Learn to build reliable scripts for operating, inspecting, and diagnosing infrastructure.
- **Azure:** Eventually apply these skills to cloud services and administration; Azure certification planning remains separate.

## Practical outcomes I want to earn

The aim is not to accumulate credentials without operational skill. I want to demonstrate that I can:

1. Explain what every part of a script does.
2. Make a script work correctly on a test system.
3. Read error messages, troubleshoot failures, and revise it.
4. Handle missing files, unavailable devices, and unexpected inputs safely.
5. Record evidence of what actually ran and what it produced.
6. Explain how the script interacts with Linux and the network.

Possible future projects include a Linux node inventory tool, service-health checks, log inspection, system reports, and radio signal metadata processing. **These are proposals; none are claimed as completed here.**

## Repository map

- [roadmap/](roadmap/) — Certification scope, sequence, and readiness criteria
- [journal/](journal/) — Dated learning and engineering records
- [exercises/](exercises/) — Small programs written and tested while learning
- [projects/](projects/) — Larger Python-specific automation work, when it exists

## Engineering record rule

Separate **planned**, **in progress**, **tested**, and **completed** work. A program is not complete just because code was written; I must run it, inspect the output, and document the result.

Baby Cloud's production or operational scripts belong in `baby-cloud`; teaching exercises, notes, and standalone Python-learning artifacts belong here. Cross-link when the same work informs both.

## Current status — 2026-10-10

**Planning / repository setup.** No Python certification has been earned through this repository, and no Python exercises are represented as tested.

Next: finish the current Linux coursework and begin Python fundamentals in small, documented exercises when study capacity allows.
