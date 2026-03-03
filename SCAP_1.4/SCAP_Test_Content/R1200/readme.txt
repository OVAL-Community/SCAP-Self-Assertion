Test Benchmark Applicability:
1. Select one of the content streams in SCAP_Test_Content\R1200 that is not applicable to the target OS
ex.  Scan Windows with MacOS content or MacOS with Linux etc..
2. SCAP interpreter should refuse to perform the scan and report that the content is not applicable to the target.
3. Then select a content stream  from SCAP_Test_Content\R1200 that is applicable to the target system
ex.  Scan Windows 11 with Windows 11 content etc..
4. SCAP interpreter should report that the content is applicable and perform the scan.

Test Rule Applicability:
- This will require either a Windows Server OS (not configured as a domain controller, or a RHEL/Oracle Linux system configured without a Gnome desktop.
1.  Review the Windows OS, and review rule results, confirming that domain controller specific rules are reported as not_applicable.
or
1.  Review an Oracle or RHEL system and review rule results, confirming that any Gnome specific requirements are reported as not_applicable.