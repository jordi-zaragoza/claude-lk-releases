# Claude-LK

Auto-sync context addon for Claude Code.

## Install

### Linux / macOS

```bash
curl -fsSL https://github.com/jordi-zaragoza/claude-lk-releases/releases/download/v1.1.0/install.sh | bash
```

### Windows (PowerShell)

```powershell
Invoke-WebRequest -Uri "https://github.com/jordi-zaragoza/claude-lk-releases/releases/download/v1.1.0/claude-lk-win.exe" -OutFile "$env:LOCALAPPDATA\claude-lk.exe"
$env:PATH += ";$env:LOCALAPPDATA"
[Environment]::SetEnvironmentVariable("PATH", $env:PATH + ";$env:LOCALAPPDATA", "User")
```

### Manual Download

| Platform | Download |
|----------|----------|
| Linux | [claude-lk-linux](https://github.com/jordi-zaragoza/claude-lk-releases/releases/download/v1.1.0/claude-lk-linux) |
| macOS | [claude-lk-macos](https://github.com/jordi-zaragoza/claude-lk-releases/releases/download/v1.1.0/claude-lk-macos) |
| Windows | [claude-lk-win.exe](https://github.com/jordi-zaragoza/claude-lk-releases/releases/download/v1.1.0/claude-lk-win.exe) |

## Setup

```bash
claude-lk activate  # Enter your license key
claude-lk setup     # Configure AI provider
```

## Usage

After setup, just use Claude Code normally:

```bash
claude
```

Context syncs automatically.

## Requirements

- License key
- Gemini or Anthropic API key

## Contact

j.z.cuffi@gmail.com

