# windows-event-labs
Hands-on Windows security logging labs focused on SOC triage using Windows Security logs + Sysmon.

## Goals
- Understand high-signal Windows Event IDs (Security + Sysmon)
- Practice process + network correlation (who did what, from where, to where)
- Produce clean evidence screenshots and repeatable lab steps

## Labs
- Lab 01: Sysmon Event ID 1 — Process Create (process tree + command-line analysis)
- Lab 02: Sysmon Event ID 3 — Network Connect (process ↔ destination correlation)
- Lab 03: Windows Security 4624/4625 — Logon Success/Failure (brute-force patterns)

## Environment
- Windows 10/11 VM
- Sysmon installed with a community config (SwiftOnSecurity or similar)
- Event Viewer (baseline) and optional Splunk later
