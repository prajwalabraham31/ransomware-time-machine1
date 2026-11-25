# Ransomware Time Machine — SOC Console Pro (Advanced)

A browser-only **simulation** of ransomware detection, containment and recovery.
Everything runs in memory on sample data. Nothing scans, touches or encrypts real files.

## Features
- 8 attack scenarios: fast burst, low-and-slow, backup wiper, double extortion, lateral worm, stealth intermittent, destructive wiper, RaaS full chain, insider abuse, APT
- Behavioural detection rules with an adjustable alert threshold
- Kill chain (MITRE ATT&CK) tracker, fleet and egress panel
- Hash-chained recovery points with one-click restore
- Run comparison: protected vs unprotected (MTTD, files lost, RTO)
- Voice assistant: spoken alerts plus voice and typed commands
- JSON incident report export

## Run it
Open `index.html` in a browser. No build step, no dependencies.

## Voice commands
"start protection", "launch worm", "run insider without protection", "restore", "verify chain", "status", "help".
Voice commands need a browser with speech recognition (Chrome or Edge) and microphone permission.

## Disclaimer
Educational demo. The risk score is a simple heuristic, not a validated rating.
