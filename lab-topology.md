# Lab Topology (example)

Topology:
- attacker (Kali-like) - used for scanning/enumeration
- target-web (Juice Shop) - intentionally vulnerable app (bound to localhost)
- monitor - tcpdump / packet capture tools

Guidelines:
- Use host-only or local network only (bind services to 127.0.0.1).
- Do not expose any lab ports to the public internet.
- Sanitize all logs and artifacts before sharing publicly.
- Snapshot VMs/containers before risky experiments so you can restore a clean state.
