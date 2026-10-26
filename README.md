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

## Troubleshooting Process

1. **System file verification:** Ran SFC to check Windows system files.
2. **Component image repair:** Used DISM to repair the Windows component image.
3. **Verification after restart:** Ran SFC again and confirmed that no integrity violations were found.
4. **Event log review:** Examined Windows System events for service errors and update-related issues.
5. **Reliability review:** Checked Reliability Monitor for unexpected shutdown records.
6. **System information:** Retrieved the last Windows boot time using PowerShell and CIM.

## Key Findings
- Windows system file verification passed after repair and restart.
- Steam Client Service startup timeouts were recorded, but Steam works normally.
- Two unexpected shutdown records were found, dated September 23 and October 19, 2026.
- A Secure Boot SBAT update failure was recorded; its cause has not been determined.

## Evidence and Findings

- [View Troubleshooting Findings](findings.txt)

The findings document includes system file verification results, DISM repair follow-up, Windows event log observations, unexpected shutdown records, and system startup information.

## Limitations
Event records provide clues, but they do not establish the root cause of every issue. No unsupported conclusions were made.

## Scope
This project used built-in diagnostic tools on my own Windows PC. Findings describe observations made during the assessment.


## Lessons Learned

- How to use SFC and DISM to check and repair Windows system files.
- How to review Windows Event Viewer logs for troubleshooting clues.
- How to use Reliability Monitor to identify unexpected shutdown events.
- How to retrieve system startup information using PowerShell and CIM.
- Why troubleshooting findings should be documented without assuming an unverified root cause.
- How to organize technical evidence and documentation in a GitHub repository.
