# Lab Setup — Safe & Isolated Environments

This repository documents a reproducible lab for cybersecurity practice (Docker / Vagrant) intended for *isolated, local use only*.

## Purpose
- Build reproducible, local labs for practicing pentesting techniques.
- Demonstrate safe configurations (bind services to localhost, private networks).
- Share non-malicious helper scripts and topology diagrams.

## Quick start (Docker)
1. Inspect docs/lab-topology.md.
2. Start lab (on your machine, not exposed to the internet):
```bash
docker compose up -d
Use the attacker container (Kali-like) and monitor for analysis.


Contents

docker-compose.yml — ready example (bound to localhost)

Vagrantfile — optional VM example

docs/ — topology and notes

scripts/ — safe helper scripts


Ethics & Safety

All setups are for educational use only in isolated environments.
Do not run these services on public production networks. Follow responsible disclosure and local laws.
