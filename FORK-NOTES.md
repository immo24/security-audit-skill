# Hinweise zu diesem Fork

Fork von [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill), angelegt am 19.08.2026 als Sicherung fuer den Coder-Workspace.

Das Original enthaelt kein Plugin-Manifest, es ist zum Kopieren nach `.claude/skills/` gedacht. Ergaenzt wurde deshalb `.claude-plugin/marketplace.json` und `.claude-plugin/plugin.json`, damit sich der Skill als Plugin installieren laesst und ueber den Marketplace aktuell gehalten werden kann. Am Skill selbst ist nichts geaendert.

Installation: `claude plugin marketplace add immo24/security-audit-skill` und `claude plugin install security-audit@cloudflare-security`.

Abgleich mit dem Original: `gh repo sync immo24/security-audit-skill`. Konflikte sind nicht zu erwarten, da nur neue Dateien hinzugekommen sind.
