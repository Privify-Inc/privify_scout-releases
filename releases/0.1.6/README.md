# Privify SCOUT 0.1.6

**AI Discovery Scanner** — single binary, no installation required.

| Platform | Binary |
|----------|--------|
| macOS (arm64 + Intel) | [scout-macos](scout-macos) |
| Linux x86\_64 | [scout-linux](scout-linux) |
| Windows x86\_64 | [scout-windows.exe](scout-windows.exe) |

## Quick start

```bash
# macOS
curl -LO https://github.com/Privify-Inc/privify_scout-releases/raw/main/releases/0.1.6/scout-macos
chmod +x scout-macos && xattr -c scout-macos && ./scout-macos

# Linux
curl -LO https://github.com/Privify-Inc/privify_scout-releases/raw/main/releases/0.1.6/scout-linux
chmod +x scout-linux && ./scout-linux

# Windows (PowerShell)
Invoke-WebRequest -Uri https://github.com/Privify-Inc/privify_scout-releases/raw/main/releases/0.1.6/scout-windows.exe -OutFile scout.exe
.\scout.exe
```

## Verify checksums

```bash
sha256sum -c checksums.txt
```
