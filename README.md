Why Did Windows Restart? 0.8.0
Publisher: ViorelPP

Purpose
-------
Why Did Windows Restart? is a Windows diagnostic utility for analyzing
restart, shutdown and crash history using Windows Event Log evidence,
BugCheck information and nearby diagnostic events.

The application is designed to help users understand why Windows restarted,
shut down unexpectedly or experienced a BSOD, while avoiding unsupported
claims of direct causation.

Free and Pro
------------
The Free edition includes:
- Local Windows restart and shutdown history analysis
- Basic restart and BSOD information
- Search and filtering
- BugCheck identification

The Pro edition additionally includes:
- EVTX file import
- Diagnostic Summary
- Nearby Critical/Error event analysis
- Diagnostic export to TXT and CSV

Pro Early Access price:
EUR 7.99 one-time purchase, including applicable sales tax where required.

Early Access customers retain Pro access through the 1.0 release
without paying the difference to the planned regular price.

A Pro license can be activated on up to 3 devices simultaneously.

License validation
------------------
Pro activation requires an Internet connection.

After a successful online validation, Pro can continue to operate offline
for up to 14 days.

If the application cannot validate the license after the offline grace
period expires, Pro features are temporarily disabled until the license
can be verified online again.

A device activation can be deactivated from within the application,
freeing one activation slot for another device.

System requirements
-------------------
Windows 10 or later
64-bit Windows

The application is distributed as a self-contained Windows x64 application.
No separate .NET installation is required.

Installation
------------
Run:

WhyDidWindowsRestart_0.8.0_x64.msi

The installer is currently not digitally signed with a public-trust
code-signing certificate.

Windows may therefore display the publisher as "Unknown" during installation.
Before running the installer, verify its SHA-256 hash against the value
published with this release.

SHA-256
-------
31A1B38741D577A171742B4AE5615D825F178131CC87C86325FDCFF2C0495A34

Verification example
--------------------
PowerShell:

Get-FileHash .\WhyDidWindowsRestart_0.8.0_x64.msi -Algorithm SHA256

The resulting hash must match the SHA-256 value published above.

Logs
----
Application diagnostic logs are stored under:

%LOCALAPPDATA%\WhyDidWindowsRestart\Logs

License information is stored locally in encrypted form using Windows
data protection mechanisms.

Privacy
-------
Why Did Windows Restart? analyzes Windows diagnostic information locally.

License activation and validation communicate with the Lemon Squeezy, 
the licensing and commerce service, in order to verify Pro license status.

The application does not intentionally upload Windows Event Log contents,
restart history, crash details or diagnostic reports to Lemon Squeezy.

Support
-------
Email:

viorelpp@proton.me

Diagnostic disclaimer
---------------------
Diagnostic clues indicate events that may warrant investigation.
They do not, by themselves, confirm causation.

Copyright
---------
Copyright © 2026 ViorelPP
