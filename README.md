# Mobile Master SKILL

Mobile security SKILL for Android reverse engineering.

## Quick Start


```bash
# Clone the skill
git clone https://github.com/Nop3z/mobile-master.git
cd mobile- master

# Install manually
cp -r ./* ~/.claude/skills/mobile-master/
```

Or manually add the path in Claude Code settings.

## Support Commands

| Script | Description |
|--------|-------------|
| [Start-frida-server](./scripts/Start-frida-server.sh) | Start frida-server on device |
| [Extract-Installation-Package](./scripts/Extract-Installation-Package.sh) | Pull APK from device |
| [spawn-app](./scripts/Spawn-app.sh) | Spawn app with frida hook |
| [attach-app](./scripts/attach-app.sh) | Attach to running app |
| [Dexdump](./scripts/Dexdump.sh) | Dump dex from memory (unpacking) |