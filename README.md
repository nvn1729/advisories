# Advisories

This repo contains writeups/references for CVEs I've found. Severity ratings are my own.

### petl (Python ETL Library)

- [CVE-2020-29128](https://nvd.nist.gov/vuln/detail/CVE-2020-29128) (_HIGH_): XXE in petl < 1.68
- Writeup: https://github.com/nvn1729/advisories/blob/master/cve-2020-29128.md

### Eramba (Governance, Risk, and Compliance Platform)

- [CVE-2020-28031](https://nvd.nist.gov/vuln/detail/CVE-2020-28031) (_MEDIUM_): Host header injection leading to authenticated full read SSRF/LFI in versions of Eramba < c2.8.1
- An authenticated, low privilege user can alter the Host header to render and download arbitrary documents using the wkhtml2pdf PDF printer.

### OrangeHRM (Human Resource Management)

- [CVE-2020-29437](https://nvd.nist.gov/vuln/detail/CVE-2020-29437) (_HIGH_): Authenticated (low-privilege) SQLi in OrangeHRM < 4.6.0.1
- Writeup: https://www.horizon3.ai/cve-2020-29437-authenticated-sql-injection-in-orangehrm-4-6-0-1/

### Acquia Mautic (Marketing Automation)

- [CVE-2020-35124](https://nvd.nist.gov/vuln/detail/CVE-2020-35124) and [CVE-2020-35125](https://nvd.nist.gov/vuln/detail/CVE-2020-35125) (_CRITICAL_): Unauthenticated stored XSS to RCE chain in Mautic < 3.24
- Writeup: https://www.horizon3.ai/unauthenticated-xss-to-remote-code-execution-chain-in-mautic-3-2-4/

### LibreNMS (Network Monitoring)

- [CVE-2020-35700](https://nvd.nist.gov/vuln/detail/CVE-2020-35700) (_HIGH_): Authenticated (low-privilege) second-order SQLi in LibreNMS < 21.1.0
- Writeup: https://www.horizon3.ai/cve-2020-35700-exploiting-a-second-order-sql-injection-in-librenms-21-1-0/

### Zabbix
- [CVE-2021-27927](https://nvd.nist.gov/vuln/detail/CVE-2021-27927) (_HIGH_): Unauth CSRF to RCE chain using an attacker controlled LDAP server to update the server's authentication settings, user interaction required
- Writeup: https://www.horizon3.ai/cve-2021-27927-csrf-to-rce-chain-in-zabbix/

### ResourceSpace (Digital Asset Management)
- [CVE-2021-41765](https://nvd.nist.gov/vuln/detail/CVE-2021-41765) (_CRITICAL_): Unauth SQLi to RCE chain in ResourceSpace 9.5/9.6
- [CVE-2021-41950](https://nvd.nist.gov/vuln/detail/CVE-2021-41950) (_HIGH_): Unauth arbitrary file deletion in ResourceSpace <= 9.6
- [CVE-2021-41951](https://nvd.nist.gov/vuln/detail/CVE-2021-41951) (_MEDIUM_): Unauth reflected XSS in ResourceSpace <= 9.6, user interaction required
- Writeup: https://www.horizon3.ai/multiple-vulnerabilities-in-resourcespace/

### ManageEngine ADAudit Plus 
- [CVE-2022-28219](https://nvd.nist.gov/vuln/detail/CVE-2022-28219) (_CRITICAL_): Unauth XXE to file upload/deserialization RCE chain in ADAudit Plus < 7060
- Writeup: https://www.horizon3.ai/red-team-blog-cve-2022-28219/

### Apache Superset
- [CVE-2023-27524](https://nvd.nist.gov/vuln/detail/CVE-2023-27524) (_CRITICAL_): Insecure Default Configuration of Flask SECRET_KEY that allows unauthenticated attackers to takeover the admin account, affecting Superset < 2.1
- [CVE-2023-30776](https://nvd.nist.gov/vuln/detail/CVE-2023-30776) (_MEDIUM_): Privileged users can see database credentials in cleartext, affecting Superset 1.3.0 to 2.0.1
- [CVE-2023-39265](https://nvd.nist.gov/vuln/detail/CVE-2023-39265) and [CVE-2023-37941](https://nvd.nist.gov/vuln/detail/CVE-2023-37941) (_HIGH_): Admin RCE chain through exposure of internal Superset configuration database and pickle deserialization RCE, affecting Superset < 2.1.1
- Writeup 1: https://www.horizon3.ai/cve-2023-27524-insecure-default-configuration-in-apache-superset-leads-to-remote-code-execution/
- Writeup 2: https://www.horizon3.ai/apache-superset-part-ii-rce-credential-harvesting-and-more/

### PaperCut (Printer Management Software)
- [CVE-2023-39143](https://nvd.nist.gov/vuln/detail/CVE-2023-39143) (_CRITICAL_): Unauth path traversal to file upload/RCE chain in PaperCut Windows versions < 22.1.3
- Advisory: https://www.horizon3.ai/cve-2023-39143-papercut-path-traversal-file-upload-rce-vulnerability/
