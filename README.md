# COMP5003: KnowBe4 North Korean Insider Threat Case Study

Analysis of July 2024 KnowBe4 incident: North Korean spy used AI deepfake + stolen identity to infiltrate as IT worker.

## 🎯 Incident Overview

**Attack Vector**:
- Stolen US identity + AI-generated photo bypassed HR screening
- Remote MacBook shipped to Washington address  
- Raspberry Pi pivoted malware (Jul 15, 9:55PM EST)
- Session history manipulation detected by SOC

**Timeline**:  
9:55PM EST: Malware deployment attempt  
10:20PM EST: Device secured (25 min response) ✅

## 📊 Key Statistics

| Metric | Value | Source |
|--------|-------|--------|
| Insider threat increase | 48% (2023→2024) | GURUCUL 2024 |
| US companies infiltrated | 300+ firms | BleepingComputer |
| Financial impact | $100M+ NK funding | US Justice Dept |
| KnowBe4 outcome | Zero data loss | SOC success |

## 🔍 MITRE ATT&CK Mapping

TA0001: Initial Access  
├── T1078: Valid Accounts (stolen identity)  
└── T1133: External Remote Services (remote Mac)  

TA0002: Execution  
└── T1059: Command Interpreter (Raspberry Pi)  

TA0007: Discovery  
└── T1087: Account Discovery (session tampering)  

## 🔓 Root Causes

- **HR/IT silos**: Background checks failed despite multi-stage process
- **AI deepfake evolution**: Video interviews bypassed  
- **Remote work risks**: Unmonitored device provisioning

## 🛡️ Mitigation Strategy

Immediate:  
├── Biometric verification (fingerprint/DNA)
├── Unified HR/IT security platform  
└── Endpoint behavioral analytics  

Strategic:  
├── Zero-trust remote access  
├── Continuous vetting (social media/OSINT)  
└── SOC playbooks for insider threats  

## 📈 Industry Context

> "93% recognize need for unified visibility, but only 36% implemented."  
> — GURUCUL 2024 Insider Threat Report

## 📄 Full Technical Report

[COMP5003-SetExercise.pdf](COMP5003-SetExercise.pdf)

**Skills Demonstrated**:  
OSINT research • MITRE ATT&CK mapping • Threat intelligence • Risk analysis • Critical evaluation
