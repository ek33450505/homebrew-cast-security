# homebrew-cast-security

Homebrew tap for [cast-security](https://github.com/ek33450505/cast-security) — security hooks and audit trail for Claude Code.

## Install

```bash
brew tap ek33450505/cast-security
brew install cast-security
cast-security install
```

## What it provides

- PreToolUse advisory threat scanner
- PermissionRequest auto-deny for sensitive paths
- SHA256 audit trail for all Write/Edit calls
- PII detection and redaction engine

## Manual install (no Homebrew)

```bash
git clone https://github.com/ek33450505/cast-security.git
cd cast-security
bash install.sh
```
