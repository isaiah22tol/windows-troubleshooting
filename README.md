# Windows Troubleshooting Project

## Overview
A beginner-level Windows troubleshooting project using built-in Windows diagnostic tools.

## Tools Used
- PowerShell
- System File Checker (SFC)
- DISM
- Windows Event Viewer
- Reliability Monitor
- Windows Management Instrumentation (CIM)

## Tasks Completed
- Checked Windows system file integrity.
- Ran DISM to repair the Windows component image.
- Re-ran SFC after restarting and verified no integrity violations were found.
- Reviewed Windows System event logs.
- Investigated Steam Client Service startup timeouts.
- Reviewed unexpected shutdown records in Reliability Monitor.
- Retrieved the last Windows boot time.

## Key Findings
- Windows system file verification passed after repair and restart.
- Steam Client Service startup timeouts were recorded, but Steam works normally.
- Two unexpected shutdown records were found, dated September 23 and October 19, 2026.
- A Secure Boot SBAT update failure was recorded; its cause has not been determined.

## Limitations
Event records provide clues, but they do not establish the root cause of every issue. No unsupported conclusions were made.

## Scope
This project used built-in diagnostic tools on my own Windows PC. Findings describe observations made during the assessment.
