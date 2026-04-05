# server-tools

Consolidated server automation and remediation scripts.

## Layout

- `tools/winrm-checker/`

## Usage Note

Run scripts only in environments and systems you own or are explicitly authorized to administer.

## Public-Safe Boundary

This repo is the public canonical for reusable server automation. Keep host inventory, FQDNs, usernames, certificates, and site-specific orchestration bindings outside the tracked tree.

## Sanitization Check

Run the repo-local guardrail before publishing changes:

```bash
bash scripts/sanitize_check.sh
```
