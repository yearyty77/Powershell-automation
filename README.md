# Powershell-automation
## System Snapshot and Change Detection Tool

### Purpose
This script captures key system configuration data and allows comparison between snapshots to identify unexpected changes after updates, installs, or incidents.

### Problem It Solves
Helpdesk and sysadmin troubleshooting often relies on assumptions. This tool provides concrete evidence of system changes, reducing guesswork and escalation time.

### What It Collects
- Installed software
- Service state and startup type
- Core system information

### How It Works
1. Takes a timestamped snapshot of the system state
2. Saves results as structured CSV files
3. Compares two snapshots and reports differences

### Example Use Case
After a Windows update, a user reports degraded performance. Comparing pre/post snapshots identifies a newly installed application and a service startup change.

### Safety Considerations
- Read-only operations only
- No system modifications
- Clear separation between data collection and comparison

### Skills Demonstrated
- PowerShell scripting
- Structured data handling
- Troubleshooting automation
- Change awareness
