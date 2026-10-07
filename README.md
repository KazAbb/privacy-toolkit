# Privacy Toolkit (working title)

A self-hosted, privacy-focused toolkit running on a hardened VPS.

## Goals
- Private grammar checking (self-hosted LanguageTool): your text never goes to a third party
- Passphrase generator with a memory-story helper, running entirely in the browser
- Hardened, documented, rebuildable infrastructure

## Status
In progress. See the checklist below.

## Roadmap
- [x] Project planned, SSH key generated
- [ ] Provision VPS and harden it (SSH keys only, firewall, auto-updates)
- [ ] Docker + LanguageTool bound to localhost
- [ ] Caddy reverse proxy with HTTPS and rate limiting
- [ ] Passphrase generator web page
- [ ] Monitoring (Uptime Kuma)
- [ ] Security test: attack my own design and write up the results

## Design decisions
(Each choice gets a short write-up: what I picked, what I rejected, and why.)
