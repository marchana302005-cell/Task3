

### *Task 3: Perform a Basic Vulnerability Scan on Your PC*

#### *Objective*
Use free tools to identify common vulnerabilities on your computer.

#### *Tools Used*
- *Tenable Nessus Essentials 10.x* - Free vulnerability scanner
- *Target*: `192.168.31.72` - Localhost, scanned my own laptop only
- *OS*: Windows 11

#### *Deliverables*
1. *Vulnerability Scan Report*: `My Basic Network Scan` completed 8/23/2026 at 1:16 PM
2. *Screenshots*: 
   - Main vulnerabilities list showing 31 total findings
   - Critical finding details page: `Oracle Database Unsupported Version Detection`
   - High finding details page
3. *Documented Vulnerabilities*: Summary of Critical and High severity issues with fixes

#### *Result: Critical Vulnerabilities Found*

**Vulnerability** | **Severity** | **CVSS v2** | **Description** | **Fix/Mitigation**
**Oracle Database Unsupported Version Detection** | Critical | 10.0 | Oracle Database 11.2.0.2.0 is no longer supported by vendor | Upgrade to a version of Oracle Database that is currently supported.
**Oracle Tns Listner Remote Poisoning** | High | 7.3 | Apply the workaround in Oracle's advisory.


*Scan Summary*: 31 total findings detected. *1 Critical, 1 High, 29 Informational*. Informational findings are not vulnerabilities and were excluded from remediation.

#### *Outcome*
Completed introductory vulnerability assessment using Nessus Essentials. Learned to: 
1. Configure and run a full system vulnerability scan safely on localhost
2. Interpret CVSS scores and severity ratings to prioritize risk
3. Use built-in `Solution` guidance to research practical mitigations
4. Identify that unsupported software is a major PC risk because it no longer receives security patches

*Key Takeaway*: Even personal laptops can have Critical risks. Running outdated database software like Oracle 11g creates a 10.0 CVSS vulnerability that allows remote compromise. The fix is simple - update or uninstall.

