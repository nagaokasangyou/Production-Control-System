# Production Control System - Differential Updates

Public differential update distribution repository for PMD.
- Main application body (PMD.exe, Java runtime, Python runtime, dependency JARs, source code) is NOT included in this repository.
- Clients automatically check and download differential updates (and authorized rollbacks) from `updates/` on startup and periodically.

## Published Update Artifacts
- `updates/version.txt`
- `updates/build-manifest.json`
- `updates/version.json`
- `updates/history.json`
- `updates/PMD_version_upgrade.zip`
- `updates/archive/v<ver>/` (recent 3 previous generations for instant rollback)
- `updates/pmd-user-monitor/version.txt`
- `updates/pmd-user-monitor/version.json`
- `updates/pmd-user-monitor/PmdUserMonitor_upgrade.zip`
