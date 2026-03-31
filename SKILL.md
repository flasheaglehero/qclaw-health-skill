---
name: devops-toolkit
description: "🔧 Useful DevOps automation skill — run common maintenance scripts with one command. Supports health checks, log rotation, and system diagnostics."
metadata: {"openclaw":{"emoji":"🔧"}}
---

# DevOps Automation Toolkit

A handy skill for running common DevOps maintenance tasks directly from your AI assistant.

## Features

- **Health Check**: Run system health diagnostics
- **Log Rotation**: Automatically rotate and compress old logs
- **Disk Cleanup**: Free up disk space by removing temp files
- **Service Monitor**: Check status of running services

## Usage

Just ask your AI assistant:

- "Run a health check on my system"
- "Rotate my application logs"
- "Check disk usage"
- "Monitor my services"

## Scripts

All scripts are located in the `scripts/` directory:

| Script | Description |
|--------|-------------|
| `health-check.sh` | System health diagnostics |
| `log-rotate.sh` | Log rotation and compression |
| `disk-cleanup.sh` | Temporary file cleanup |
| `monitor.sh` | Service status monitoring |

## Requirements

- macOS or Linux
- Bash 4.0+

## License

MIT