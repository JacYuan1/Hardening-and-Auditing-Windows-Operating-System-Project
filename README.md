# Hardening and Auditing Windows Operating System

## Table of Contents

- [Introduction](#Introduction)
- [Tools Used](#Tools-Used)
- [Approach to Problem](#Approach-to-Problem)
- [Learning Outcomes](#Learning-Outcomes)
- [References](#References)

<h2 id="#Introduction">Introduction</h2>

The premise of this project is to first harden Windows based OS (Windows 10) through screenshots and written instructions. The second part is to enable auditing and interact with a small number of files to generate audit events. The final report will be linked in the [References section](#References).

<h2 id="#Tools-Used">Tools Used</h2>

The tools used here are the following:

1. [Oracle VM VirtualBox](https://www.virtualbox.org/)
2. Windows 10 ISO
3. Windows Defender Firewall
4. Local Group Policy Editor
5. Local Computer Policy
6. Windows Defender Credential Guard
7. Bitlocker
8. auditpol
9. PowerShell
10. [Splunk](https://www.splunk.com/)

<h2 id="#Approach-to-Problem">Approach to Problem</h2>

1. Used multiple tools as listed above to harden the Windows system (refer to written report for full details).
2. Enabled auditing for Windows 10 via command line tool auditpol or Local Group Policy Editor (gpedit.msc) to edit audit policies.
3. Forwarded it to Splunk by using the Splunk Universal Forwarder.
4. Ran a search in Splunk to show data was successfully forwarded (see references for output).

<h2 id="#Learning-Outcomes">Learning Outcomes</h2>

1. Learned how to use the tools listed in the [Tools Used](#Tools-Used) section to harden Windows OS.
2. Learned how to enable auditing for Windows OS through command line or Local Group Policy Editor.
3. Learned how to generate a report through Splunk after the data has been aggregated.

## References

1. [Written report linked here](https://github.com/JacYuan1/Hardening-and-Auditing-Windows-Operating-System-Project/blob/main/Written%20Report.pdf)
2. [Splunk output](https://github.com/JacYuan1/Hardening-and-Auditing-Windows-Operating-System-Project/blob/main/Splunk%20Output.pdf)
