# 2023 List

---
## CVE-2023-34362 (2023-06-02T14:15:00)
> In Progress MOVEit Transfer before 2021.0.6 (13.0.6), 2021.1.4 (13.1.4), 2022.0.4 (14.0.4), 2022.1.5 (14.1.5), and 2023.0.1 (15.0.1), a SQL injection vulnerability has been found in the MOVEit Transfer web application that could allow an unauthenticated attacker to gain access to MOVEit Transfer's database. Depending on the database engine being used (MySQL, Microsoft SQL Server, or Azure SQL), an attacker may be able to infer information about the structure and contents of the database, and execute SQL statements that alter or delete database elements. NOTE: this is exploited in the wild in May and June 2023; exploitation of unpatched systems can occur via HTTP or HTTPS. All versions (e.g., 2020.0 and 2019x) before the five explicitly mentioned versions are affected, including older unsupported versions.
- [deepinstinct/MOVEit_CVE-2023-34362_IOCs](https://github.com/deepinstinct/MOVEit_CVE-2023-34362_IOCs)	<img alt="forks" src="https://img.shields.io/github/forks/deepinstinct/MOVEit_CVE-2023-34362_IOCs">	<img alt="stars" src="https://img.shields.io/github/stars/deepinstinct/MOVEit_CVE-2023-34362_IOCs">
- [a3cipher/CVE-2023-34362](https://github.com/a3cipher/CVE-2023-34362)	<img alt="forks" src="https://img.shields.io/github/forks/a3cipher/CVE-2023-34362">	<img alt="stars" src="https://img.shields.io/github/stars/a3cipher/CVE-2023-34362">
- [hheeyywweellccoommee/CVE-2023-34362-nhjxn](https://github.com/hheeyywweellccoommee/CVE-2023-34362-nhjxn)	<img alt="forks" src="https://img.shields.io/github/forks/hheeyywweellccoommee/CVE-2023-34362-nhjxn">	<img alt="stars" src="https://img.shields.io/github/stars/hheeyywweellccoommee/CVE-2023-34362-nhjxn">

---
## CVE-2023-33977 (2023-06-06T19:15:00)
> Kiwi TCMS is an open source test management system for both manual and automated testing. Kiwi TCMS allows users to upload attachments to test plans, test cases, etc. Earlier versions of Kiwi TCMS had introduced upload validators in order to prevent potentially dangerous files from being uploaded and Content-Security-Policy definition to prevent cross-site-scripting attacks. The upload validation checks were not 100% robust which left the possibility to circumvent them and upload a potentially dangerous file which allows execution of arbitrary JavaScript in the browser. Additionally we've discovered that Nginx's `proxy_pass` directive will strip some headers negating protections built into Kiwi TCMS when served behind a reverse proxy. This issue has been addressed in version 12.4. Users are advised to upgrade. Users unable to upgrade who are serving Kiwi TCMS behind a reverse proxy should make sure that additional header values are still passed to the client browser. If they aren't redefining them inside the proxy configuration.
- [mnqazi/CVE-2023-33977](https://github.com/mnqazi/CVE-2023-33977)	<img alt="forks" src="https://img.shields.io/github/forks/mnqazi/CVE-2023-33977">	<img alt="stars" src="https://img.shields.io/github/stars/mnqazi/CVE-2023-33977">

---
## CVE-2023-33829 (2023-05-24T21:15:00)
> A stored cross-site scripting (XSS) vulnerability in Cloudogu GmbH SCM Manager v1.2 to v1.60 allows attackers to execute arbitrary web scripts or HTML via a crafted payload injected into the Description text field.
- [CKevens/CVE-2023-33829-POC](https://github.com/CKevens/CVE-2023-33829-POC)	<img alt="forks" src="https://img.shields.io/github/forks/CKevens/CVE-2023-33829-POC">	<img alt="stars" src="https://img.shields.io/github/stars/CKevens/CVE-2023-33829-POC">
- [n3gox/CVE-2023-33829](https://github.com/n3gox/CVE-2023-33829)	<img alt="forks" src="https://img.shields.io/github/forks/n3gox/CVE-2023-33829">	<img alt="stars" src="https://img.shields.io/github/stars/n3gox/CVE-2023-33829">

---
## CVE-2023-33782 (2023-06-07T01:15:00)
> D-Link DIR-842V2 v1.0.3 was discovered to contain a command injection vulnerability via the iperf3 diagnostics function.
- [s0tr/CVE-2023-33782](https://github.com/s0tr/CVE-2023-33782)	<img alt="forks" src="https://img.shields.io/github/forks/s0tr/CVE-2023-33782">	<img alt="stars" src="https://img.shields.io/github/stars/s0tr/CVE-2023-33782">

---
## CVE-2023-33781 (2023-06-07T01:15:00)
> An issue in D-Link DIR-842V2 v1.0.3 allows attackers to execute arbitrary commands via importing a crafted file.
- [s0tr/CVE-2023-33781](https://github.com/s0tr/CVE-2023-33781)	<img alt="forks" src="https://img.shields.io/github/forks/s0tr/CVE-2023-33781">	<img alt="stars" src="https://img.shields.io/github/stars/s0tr/CVE-2023-33781">

---
## CVE-2023-33477 (2023-06-06T20:15:00)
> In Harmonic NSG 9000-6G devices, an authenticated remote user can obtain source code by directly requesting a special path.
- [Skr11lex/CVE-2023-33477](https://github.com/Skr11lex/CVE-2023-33477)	<img alt="forks" src="https://img.shields.io/github/forks/Skr11lex/CVE-2023-33477">	<img alt="stars" src="https://img.shields.io/github/stars/Skr11lex/CVE-2023-33477">

---
## CVE-2023-33410 (2023-06-05T21:15:00)
> Minical 1.0.0 and earlier contains a CSV injection vulnerability which allows an attacker to execute remote code. The vulnerability exists due to insufficient input validation on the Customer Name field in the Accounting module that is used to construct a CSV file.
- [Thirukrishnan/CVE-2023-33410](https://github.com/Thirukrishnan/CVE-2023-33410)	<img alt="forks" src="https://img.shields.io/github/forks/Thirukrishnan/CVE-2023-33410">	<img alt="stars" src="https://img.shields.io/github/stars/Thirukrishnan/CVE-2023-33410">

---
## CVE-2023-33409 (2023-06-05T21:15:00)
> Minical 1.0.0 is vulnerable to Cross Site Request Forgery (CSRF) via minical/public/application/controllers/settings/company.php.
- [Thirukrishnan/CVE-2023-33409](https://github.com/Thirukrishnan/CVE-2023-33409)	<img alt="forks" src="https://img.shields.io/github/forks/Thirukrishnan/CVE-2023-33409">	<img alt="stars" src="https://img.shields.io/github/stars/Thirukrishnan/CVE-2023-33409">

---
## CVE-2023-33408 (2023-06-05T21:15:00)
> Minical 1.0.0 is vulnerable to Cross Site Scripting (XSS). The vulnerability exists due to insufficient input validation in the application's user input handling in the security_helper.php file.
- [Thirukrishnan/CVE-2023-33408](https://github.com/Thirukrishnan/CVE-2023-33408)	<img alt="forks" src="https://img.shields.io/github/forks/Thirukrishnan/CVE-2023-33408">	<img alt="stars" src="https://img.shields.io/github/stars/Thirukrishnan/CVE-2023-33408">

---
## CVE-2023-33246 (2023-05-24T15:15:00)
> For RocketMQ versions 5.1.0 and below, under certain conditions, there is a risk of remote command execution. 

Several components of RocketMQ, including NameServer, Broker, and Controller, are leaked on the extranet and lack permission verification, an attacker can exploit this vulnerability by using the update configuration function to execute commands as the system users that RocketMQ is running as. Additionally, an attacker can achieve the same effect by forging the RocketMQ protocol content. 

To prevent these attacks, users are recommended to upgrade to version 5.1.1 or above for using RocketMQ 5.x or 4.9.6 or above for using RocketMQ 4.x .












- [Malayke/CVE-2023-33246_RocketMQ_RCE_EXPLOIT](https://github.com/Malayke/CVE-2023-33246_RocketMQ_RCE_EXPLOIT)	<img alt="forks" src="https://img.shields.io/github/forks/Malayke/CVE-2023-33246_RocketMQ_RCE_EXPLOIT">	<img alt="stars" src="https://img.shields.io/github/stars/Malayke/CVE-2023-33246_RocketMQ_RCE_EXPLOIT">
- [Le1a/CVE-2023-33246](https://github.com/Le1a/CVE-2023-33246)	<img alt="forks" src="https://img.shields.io/github/forks/Le1a/CVE-2023-33246">	<img alt="stars" src="https://img.shields.io/github/stars/Le1a/CVE-2023-33246">
- [CKevens/CVE-2023-33246](https://github.com/CKevens/CVE-2023-33246)	<img alt="forks" src="https://img.shields.io/github/forks/CKevens/CVE-2023-33246">	<img alt="stars" src="https://img.shields.io/github/stars/CKevens/CVE-2023-33246">
- [SuperZero/CVE-2023-33246](https://github.com/SuperZero/CVE-2023-33246)	<img alt="forks" src="https://img.shields.io/github/forks/SuperZero/CVE-2023-33246">	<img alt="stars" src="https://img.shields.io/github/stars/SuperZero/CVE-2023-33246">
- [yizhimanpadewoniu/CVE-2023-33246-Copy](https://github.com/yizhimanpadewoniu/CVE-2023-33246-Copy)	<img alt="forks" src="https://img.shields.io/github/forks/yizhimanpadewoniu/CVE-2023-33246-Copy">	<img alt="stars" src="https://img.shields.io/github/stars/yizhimanpadewoniu/CVE-2023-33246-Copy">
- [I5N0rth/CVE-2023-33246](https://github.com/I5N0rth/CVE-2023-33246)	<img alt="forks" src="https://img.shields.io/github/forks/I5N0rth/CVE-2023-33246">	<img alt="stars" src="https://img.shields.io/github/stars/I5N0rth/CVE-2023-33246">
- [Serendipity-Lucky/CVE-2023-33246](https://github.com/Serendipity-Lucky/CVE-2023-33246)	<img alt="forks" src="https://img.shields.io/github/forks/Serendipity-Lucky/CVE-2023-33246">	<img alt="stars" src="https://img.shields.io/github/stars/Serendipity-Lucky/CVE-2023-33246">
- [hheeyywweellccoommee/CVE-2023-33246-rnkku](https://github.com/hheeyywweellccoommee/CVE-2023-33246-rnkku)	<img alt="forks" src="https://img.shields.io/github/forks/hheeyywweellccoommee/CVE-2023-33246-rnkku">	<img alt="stars" src="https://img.shields.io/github/stars/hheeyywweellccoommee/CVE-2023-33246-rnkku">

---
## CVE-2023-33243 ()
> 
- [RedTeamPentesting/CVE-2023-33243](https://github.com/RedTeamPentesting/CVE-2023-33243)	<img alt="forks" src="https://img.shields.io/github/forks/RedTeamPentesting/CVE-2023-33243">	<img alt="stars" src="https://img.shields.io/github/stars/RedTeamPentesting/CVE-2023-33243">

---
## CVE-2023-32243 (2023-05-12T08:15:00)
> Improper Authentication vulnerability in WPDeveloper Essential Addons for Elementor allows Privilege Escalation. This issue affects Essential Addons for Elementor: from 5.4.0 through 5.7.1.
- [RandomRobbieBF/CVE-2023-32243](https://github.com/RandomRobbieBF/CVE-2023-32243)	<img alt="forks" src="https://img.shields.io/github/forks/RandomRobbieBF/CVE-2023-32243">	<img alt="stars" src="https://img.shields.io/github/stars/RandomRobbieBF/CVE-2023-32243">
- [gbrsh/CVE-2023-32243](https://github.com/gbrsh/CVE-2023-32243)	<img alt="forks" src="https://img.shields.io/github/forks/gbrsh/CVE-2023-32243">	<img alt="stars" src="https://img.shields.io/github/stars/gbrsh/CVE-2023-32243">
- [thatonesecguy/Wordpress-Vulnerability-Identification-Scripts](https://github.com/thatonesecguy/Wordpress-Vulnerability-Identification-Scripts)	<img alt="forks" src="https://img.shields.io/github/forks/thatonesecguy/Wordpress-Vulnerability-Identification-Scripts">	<img alt="stars" src="https://img.shields.io/github/stars/thatonesecguy/Wordpress-Vulnerability-Identification-Scripts">
- [YouGina/CVE-2023-32243](https://github.com/YouGina/CVE-2023-32243)	<img alt="forks" src="https://img.shields.io/github/forks/YouGina/CVE-2023-32243">	<img alt="stars" src="https://img.shields.io/github/stars/YouGina/CVE-2023-32243">
- [manavvedawala/CVE-2023-32243-proof-of-concept](https://github.com/manavvedawala/CVE-2023-32243-proof-of-concept)	<img alt="forks" src="https://img.shields.io/github/forks/manavvedawala/CVE-2023-32243-proof-of-concept">	<img alt="stars" src="https://img.shields.io/github/stars/manavvedawala/CVE-2023-32243-proof-of-concept">
- [manavvedawala/CVE-2023-32243-POC](https://github.com/manavvedawala/CVE-2023-32243-POC)	<img alt="forks" src="https://img.shields.io/github/forks/manavvedawala/CVE-2023-32243-POC">	<img alt="stars" src="https://img.shields.io/github/stars/manavvedawala/CVE-2023-32243-POC">
- [hheeyywweellccoommee/Mass-CVE-2023-32243-kcpqa](https://github.com/hheeyywweellccoommee/Mass-CVE-2023-32243-kcpqa)	<img alt="forks" src="https://img.shields.io/github/forks/hheeyywweellccoommee/Mass-CVE-2023-32243-kcpqa">	<img alt="stars" src="https://img.shields.io/github/stars/hheeyywweellccoommee/Mass-CVE-2023-32243-kcpqa">
- [little44n1o/cve-2023-32243](https://github.com/little44n1o/cve-2023-32243)	<img alt="forks" src="https://img.shields.io/github/forks/little44n1o/cve-2023-32243">	<img alt="stars" src="https://img.shields.io/github/stars/little44n1o/cve-2023-32243">

---
## CVE-2023-31606 (2023-06-06T17:15:00)
> A Regular Expression Denial of Service (ReDoS) issue was discovered in the sanitize_html function of redcloth gem v4.0.0. This vulnerability allows attackers to cause a Denial of Service (DoS) via supplying a crafted payload.
- [e23e/CVE-2023-31606](https://github.com/e23e/CVE-2023-31606)	<img alt="forks" src="https://img.shields.io/github/forks/e23e/CVE-2023-31606">	<img alt="stars" src="https://img.shields.io/github/stars/e23e/CVE-2023-31606">

---
## CVE-2023-29325 (2023-05-09T18:15:00)
> Windows OLE Remote Code Execution Vulnerability
- [a-bazi/test-CVE-2023-29325](https://github.com/a-bazi/test-CVE-2023-29325)	<img alt="forks" src="https://img.shields.io/github/forks/a-bazi/test-CVE-2023-29325">	<img alt="stars" src="https://img.shields.io/github/stars/a-bazi/test-CVE-2023-29325">

---
## CVE-2023-28771 (2023-04-25T02:15:00)
> Improper error message handling in Zyxel ZyWALL/USG series firmware versions 4.60 through 4.73, VPN series firmware versions 4.60 through 5.35, USG FLEX series firmware versions 4.60 through 5.35, and ATP series firmware versions 4.60 through 5.35, which could allow an unauthenticated attacker to execute some OS commands remotely by sending crafted packets to an affected device.
- [WhiteOwl-Pub/PoC-CVE-2023-28771](https://github.com/WhiteOwl-Pub/PoC-CVE-2023-28771)	<img alt="forks" src="https://img.shields.io/github/forks/WhiteOwl-Pub/PoC-CVE-2023-28771">	<img alt="stars" src="https://img.shields.io/github/stars/WhiteOwl-Pub/PoC-CVE-2023-28771">
- [AKuzmanHSCS/Microsoft-Exchange-RCE](https://github.com/AKuzmanHSCS/Microsoft-Exchange-RCE)	<img alt="forks" src="https://img.shields.io/github/forks/AKuzmanHSCS/Microsoft-Exchange-RCE">	<img alt="stars" src="https://img.shields.io/github/stars/AKuzmanHSCS/Microsoft-Exchange-RCE">
- [DLandonHSCS/Discord-RCE](https://github.com/DLandonHSCS/Discord-RCE)	<img alt="forks" src="https://img.shields.io/github/forks/DLandonHSCS/Discord-RCE">	<img alt="stars" src="https://img.shields.io/github/stars/DLandonHSCS/Discord-RCE">
- [BenHays142/CVE-2023-28771-PoC](https://github.com/BenHays142/CVE-2023-28771-PoC)	<img alt="forks" src="https://img.shields.io/github/forks/BenHays142/CVE-2023-28771-PoC">	<img alt="stars" src="https://img.shields.io/github/stars/BenHays142/CVE-2023-28771-PoC">

---
## CVE-2023-2825 (2023-05-26T21:15:00)
> An issue has been discovered in GitLab CE/EE affecting only version 16.0.0. An unauthenticated malicious user can use a path traversal vulnerability to read arbitrary files on the server when an attachment exists in a public project nested within at least five groups.
- [Occamsec/CVE-2023-2825](https://github.com/Occamsec/CVE-2023-2825)	<img alt="forks" src="https://img.shields.io/github/forks/Occamsec/CVE-2023-2825">	<img alt="stars" src="https://img.shields.io/github/stars/Occamsec/CVE-2023-2825">
- [Tornad0007/CVE-2023-2825-Gitlab](https://github.com/Tornad0007/CVE-2023-2825-Gitlab)	<img alt="forks" src="https://img.shields.io/github/forks/Tornad0007/CVE-2023-2825-Gitlab">	<img alt="stars" src="https://img.shields.io/github/stars/Tornad0007/CVE-2023-2825-Gitlab">
- [yuimarudev/CVE-2023-2825](https://github.com/yuimarudev/CVE-2023-2825)	<img alt="forks" src="https://img.shields.io/github/forks/yuimarudev/CVE-2023-2825">	<img alt="stars" src="https://img.shields.io/github/stars/yuimarudev/CVE-2023-2825">
- [EmmanuelCruzL/CVE-2023-2825](https://github.com/EmmanuelCruzL/CVE-2023-2825)	<img alt="forks" src="https://img.shields.io/github/forks/EmmanuelCruzL/CVE-2023-2825">	<img alt="stars" src="https://img.shields.io/github/stars/EmmanuelCruzL/CVE-2023-2825">

---
## CVE-2023-28178 (2023-05-08T20:15:00)
> A logic issue was addressed with improved validation. This issue is fixed in macOS Monterey 12.6.4, iOS 16.4 and iPadOS 16.4, macOS Ventura 13.3. An app may be able to bypass Privacy preferences
- [MacCVEResearch/CVE-2023-28178-patch](https://github.com/MacCVEResearch/CVE-2023-28178-patch)	<img alt="forks" src="https://img.shields.io/github/forks/MacCVEResearch/CVE-2023-28178-patch">	<img alt="stars" src="https://img.shields.io/github/stars/MacCVEResearch/CVE-2023-28178-patch">

---
## CVE-2023-2732 (2023-05-25T03:15:00)
> The MStore API plugin for WordPress is vulnerable to authentication bypass in versions up to, and including, 3.9.2. This is due to insufficient verification on the user being supplied during the add listing REST API request through the plugin. This makes it possible for unauthenticated attackers to log in as any existing user on the site, such as an administrator, if they have access to the user id.
- [Jenderal92/WP-CVE-2023-2732](https://github.com/Jenderal92/WP-CVE-2023-2732)	<img alt="forks" src="https://img.shields.io/github/forks/Jenderal92/WP-CVE-2023-2732">	<img alt="stars" src="https://img.shields.io/github/stars/Jenderal92/WP-CVE-2023-2732">
- [domainhigh/CVE-2023-2732-Mass](https://github.com/domainhigh/CVE-2023-2732-Mass)	<img alt="forks" src="https://img.shields.io/github/forks/domainhigh/CVE-2023-2732-Mass">	<img alt="stars" src="https://img.shields.io/github/stars/domainhigh/CVE-2023-2732-Mass">
- [RandomRobbieBF/CVE-2023-2732](https://github.com/RandomRobbieBF/CVE-2023-2732)	<img alt="forks" src="https://img.shields.io/github/forks/RandomRobbieBF/CVE-2023-2732">	<img alt="stars" src="https://img.shields.io/github/stars/RandomRobbieBF/CVE-2023-2732">
- [Malwareman007/CVE-2023-27326](https://github.com/Malwareman007/CVE-2023-27326)	<img alt="forks" src="https://img.shields.io/github/forks/Malwareman007/CVE-2023-27326">	<img alt="stars" src="https://img.shields.io/github/stars/Malwareman007/CVE-2023-27326">
- [Impalabs/CVE-2023-27326](https://github.com/Impalabs/CVE-2023-27326)	<img alt="forks" src="https://img.shields.io/github/forks/Impalabs/CVE-2023-27326">	<img alt="stars" src="https://img.shields.io/github/stars/Impalabs/CVE-2023-27326">

---
## CVE-2023-2650 (2023-05-30T14:15:00)
> Issue summary: Processing some specially crafted ASN.1 object identifiers or
data containing them may be very slow.

Impact summary: Applications that use OBJ_obj2txt() directly, or use any of
the OpenSSL subsystems OCSP, PKCS7/SMIME, CMS, CMP/CRMF or TS with no message
size limit may experience notable to very long delays when processing those
messages, which may lead to a Denial of Service.

An OBJECT IDENTIFIER is composed of a series of numbers - sub-identifiers -
most of which have no size limit.  OBJ_obj2txt() may be used to translate
an ASN.1 OBJECT IDENTIFIER given in DER encoding form (using the OpenSSL
type ASN1_OBJECT) to its canonical numeric text form, which are the
sub-identifiers of the OBJECT IDENTIFIER in decimal form, separated by
periods.

When one of the sub-identifiers in the OBJECT IDENTIFIER is very large
(these are sizes that are seen as absurdly large, taking up tens or hundreds
of KiBs), the translation to a decimal number in text may take a very long
time.  The time complexity is O(n^2) with 'n' being the size of the
sub-identifiers in bytes (*).

With OpenSSL 3.0, support to fetch cryptographic algorithms using names /
identifiers in string form was introduced.  This includes using OBJECT
IDENTIFIERs in canonical numeric text form as identifiers for fetching
algorithms.

Such OBJECT IDENTIFIERs may be received through the ASN.1 structure
AlgorithmIdentifier, which is commonly used in multiple protocols to specify
what cryptographic algorithm should be used to sign or verify, encrypt or
decrypt, or digest passed data.

Applications that call OBJ_obj2txt() directly with untrusted data are
affected, with any version of OpenSSL.  If the use is for the mere purpose
of display, the severity is considered low.

In OpenSSL 3.0 and newer, this affects the subsystems OCSP, PKCS7/SMIME,
CMS, CMP/CRMF or TS.  It also impacts anything that processes X.509
certificates, including simple things like verifying its signature.

The impact on TLS is relatively low, because all versions of OpenSSL have a
100KiB limit on the peer's certificate chain.  Additionally, this only
impacts clients, or servers that have explicitly enabled client
authentication.

In OpenSSL 1.1.1 and 1.0.2, this only affects displaying diverse objects,
such as X.509 certificates.  This is assumed to not happen in such a way
that it would cause a Denial of Service, so these versions are considered
not affected by this issue in such a way that it would be cause for concern,
and the severity is therefore considered low.
- [hshivhare67/OpenSSL_1.1.1g_CVE-2023-2650](https://github.com/hshivhare67/OpenSSL_1.1.1g_CVE-2023-2650)	<img alt="forks" src="https://img.shields.io/github/forks/hshivhare67/OpenSSL_1.1.1g_CVE-2023-2650">	<img alt="stars" src="https://img.shields.io/github/stars/hshivhare67/OpenSSL_1.1.1g_CVE-2023-2650">

---
## CVE-2023-25690 (2023-03-07T16:15:00)
> Some mod_proxy configurations on Apache HTTP Server versions 2.4.0 through 2.4.55 allow a HTTP Request Smuggling attack.




Configurations are affected when mod_proxy is enabled along with some form of RewriteRule
 or ProxyPassMatch in which a non-specific pattern matches
 some portion of the user-supplied request-target (URL) data and is then
 re-inserted into the proxied request-target using variable 
substitution. For example, something like:




RewriteEngine on
RewriteRule "^/here/(.*)" "http://example.com:8080/elsewhere?$1"; [P]
ProxyPassReverse /here/ http://example.com:8080/


Request splitting/smuggling could result in bypass of access controls in the proxy server, proxying unintended URLs to existing origin servers, and cache poisoning. Users are recommended to update to at least version 2.4.56 of Apache HTTP Server.



- [dhmosfunk/CVE-2023-25690-POC](https://github.com/dhmosfunk/CVE-2023-25690-POC)	<img alt="forks" src="https://img.shields.io/github/forks/dhmosfunk/CVE-2023-25690-POC">	<img alt="stars" src="https://img.shields.io/github/stars/dhmosfunk/CVE-2023-25690-POC">
- [tbachvarova/linux-apache-fix-mod_rewrite-spaceInURL](https://github.com/tbachvarova/linux-apache-fix-mod_rewrite-spaceInURL)	<img alt="forks" src="https://img.shields.io/github/forks/tbachvarova/linux-apache-fix-mod_rewrite-spaceInURL">	<img alt="stars" src="https://img.shields.io/github/stars/tbachvarova/linux-apache-fix-mod_rewrite-spaceInURL">

---
## CVE-2023-25157 (2023-02-21T22:15:00)
> GeoServer is an open source software server written in Java that allows users to share and edit geospatial data. GeoServer includes support for the OGC Filter expression language and the OGC Common Query Language (CQL) as part of the Web Feature Service (WFS) and Web Map Service (WMS) protocols. CQL is also supported through the Web Coverage Service (WCS) protocol for ImageMosaic coverages. Users are advised to upgrade to either version 2.21.4, or version 2.22.2 to resolve this issue. Users unable to upgrade should disable the PostGIS Datastore *encode functions* setting to mitigate ``strEndsWith``, ``strStartsWith`` and ``PropertyIsLike `` misuse and enable the PostGIS DataStore *preparedStatements* setting to mitigate the ``FeatureId`` misuse.
- [win3zz/CVE-2023-25157](https://github.com/win3zz/CVE-2023-25157)	<img alt="forks" src="https://img.shields.io/github/forks/win3zz/CVE-2023-25157">	<img alt="stars" src="https://img.shields.io/github/stars/win3zz/CVE-2023-25157">

---
## CVE-2023-25136 (2023-02-03T06:15:00)
> OpenSSH server (sshd) 9.1 introduced a double-free vulnerability during options.kex_algorithms handling. This is fixed in OpenSSH 9.2. The double free can be leveraged, by an unauthenticated remote attacker in the default configuration, to jump to any location in the sshd address space. One third-party report states "remote code execution is theoretically possible."
- [axylisdead/CVE-2023-25136_POC](https://github.com/axylisdead/CVE-2023-25136_POC)	<img alt="forks" src="https://img.shields.io/github/forks/axylisdead/CVE-2023-25136_POC">	<img alt="stars" src="https://img.shields.io/github/stars/axylisdead/CVE-2023-25136_POC">
- [nhakobyan685/CVE-2023-25136](https://github.com/nhakobyan685/CVE-2023-25136)	<img alt="forks" src="https://img.shields.io/github/forks/nhakobyan685/CVE-2023-25136">	<img alt="stars" src="https://img.shields.io/github/stars/nhakobyan685/CVE-2023-25136">
- [adhikara13/CVE-2023-25136](https://github.com/adhikara13/CVE-2023-25136)	<img alt="forks" src="https://img.shields.io/github/forks/adhikara13/CVE-2023-25136">	<img alt="stars" src="https://img.shields.io/github/stars/adhikara13/CVE-2023-25136">
- [Christbowel/CVE-2023-25136](https://github.com/Christbowel/CVE-2023-25136)	<img alt="forks" src="https://img.shields.io/github/forks/Christbowel/CVE-2023-25136">	<img alt="stars" src="https://img.shields.io/github/stars/Christbowel/CVE-2023-25136">
- [ticofookfook/CVE-2023-25136](https://github.com/ticofookfook/CVE-2023-25136)	<img alt="forks" src="https://img.shields.io/github/forks/ticofookfook/CVE-2023-25136">	<img alt="stars" src="https://img.shields.io/github/stars/ticofookfook/CVE-2023-25136">
- [jfrog/jfrog-CVE-2023-25136-OpenSSH_Double-Free](https://github.com/jfrog/jfrog-CVE-2023-25136-OpenSSH_Double-Free)	<img alt="forks" src="https://img.shields.io/github/forks/jfrog/jfrog-CVE-2023-25136-OpenSSH_Double-Free">	<img alt="stars" src="https://img.shields.io/github/stars/jfrog/jfrog-CVE-2023-25136-OpenSSH_Double-Free">

---
## CVE-2023-23638 (2023-03-08T11:15:00)
> A deserialization vulnerability existed when dubbo generic invoke, which could lead to malicious code execution. This issue affects Apache Dubbo 2.7.x version 2.7.21 and prior versions; Apache Dubbo 3.0.x version 3.0.13 and prior versions; Apache Dubbo 3.1.x version 3.1.5 and prior versions.
- [YYHYlh/Apache-Dubbo-CVE-2023-23638-exp](https://github.com/YYHYlh/Apache-Dubbo-CVE-2023-23638-exp)	<img alt="forks" src="https://img.shields.io/github/forks/YYHYlh/Apache-Dubbo-CVE-2023-23638-exp">	<img alt="stars" src="https://img.shields.io/github/stars/YYHYlh/Apache-Dubbo-CVE-2023-23638-exp">
- [X1r0z/CVE-2023-23638](https://github.com/X1r0z/CVE-2023-23638)	<img alt="forks" src="https://img.shields.io/github/forks/X1r0z/CVE-2023-23638">	<img alt="stars" src="https://img.shields.io/github/stars/X1r0z/CVE-2023-23638">

---
## CVE-2023-23488 (2023-01-20T18:15:00)
> The Paid Memberships Pro WordPress Plugin, version < 2.9.8, is affected by an unauthenticated SQL injection vulnerability in the 'code' parameter of the '/pmpro/v1/order' REST route.
- [cybfar/CVE-2023-23488-pmpro-2.8](https://github.com/cybfar/CVE-2023-23488-pmpro-2.8)	<img alt="forks" src="https://img.shields.io/github/forks/cybfar/CVE-2023-23488-pmpro-2.8">	<img alt="stars" src="https://img.shields.io/github/stars/cybfar/CVE-2023-23488-pmpro-2.8">
- [r3nt0n/CVE-2023-23488-PoC](https://github.com/r3nt0n/CVE-2023-23488-PoC)	<img alt="forks" src="https://img.shields.io/github/forks/r3nt0n/CVE-2023-23488-PoC">	<img alt="stars" src="https://img.shields.io/github/stars/r3nt0n/CVE-2023-23488-PoC">

---
## CVE-2023-21839 (2023-01-18T00:15:00)
> Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Core).  Supported versions that are affected are 12.2.1.3.0, 12.2.1.4.0 and  14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via T3, IIOP to compromise Oracle WebLogic Server.  Successful attacks of this vulnerability can result in  unauthorized access to critical data or complete access to all Oracle WebLogic Server accessible data. CVSS 3.1 Base Score 7.5 (Confidentiality impacts).  CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N).
- [kw3h4/CVE-2023-21839-metasploit-scanner](https://github.com/kw3h4/CVE-2023-21839-metasploit-scanner)	<img alt="forks" src="https://img.shields.io/github/forks/kw3h4/CVE-2023-21839-metasploit-scanner">	<img alt="stars" src="https://img.shields.io/github/stars/kw3h4/CVE-2023-21839-metasploit-scanner">
- [RShahHSCS/Discord-0-Day-Exploit](https://github.com/RShahHSCS/Discord-0-Day-Exploit)	<img alt="forks" src="https://img.shields.io/github/forks/RShahHSCS/Discord-0-Day-Exploit">	<img alt="stars" src="https://img.shields.io/github/stars/RShahHSCS/Discord-0-Day-Exploit">
- [AKuzmanHSCS/Microsoft-Exchange-RCE](https://github.com/AKuzmanHSCS/Microsoft-Exchange-RCE)	<img alt="forks" src="https://img.shields.io/github/forks/AKuzmanHSCS/Microsoft-Exchange-RCE">	<img alt="stars" src="https://img.shields.io/github/stars/AKuzmanHSCS/Microsoft-Exchange-RCE">
- [gobysec/Weblogic](https://github.com/gobysec/Weblogic)	<img alt="forks" src="https://img.shields.io/github/forks/gobysec/Weblogic">	<img alt="stars" src="https://img.shields.io/github/stars/gobysec/Weblogic">
- [4ra1n/CVE-2023-21839](https://github.com/4ra1n/CVE-2023-21839)	<img alt="forks" src="https://img.shields.io/github/forks/4ra1n/CVE-2023-21839">	<img alt="stars" src="https://img.shields.io/github/stars/4ra1n/CVE-2023-21839">
- [houqe/POC_CVE-2023-21839](https://github.com/houqe/POC_CVE-2023-21839)	<img alt="forks" src="https://img.shields.io/github/forks/houqe/POC_CVE-2023-21839">	<img alt="stars" src="https://img.shields.io/github/stars/houqe/POC_CVE-2023-21839">
- [Firebasky/CVE-2023-21839](https://github.com/Firebasky/CVE-2023-21839)	<img alt="forks" src="https://img.shields.io/github/forks/Firebasky/CVE-2023-21839">	<img alt="stars" src="https://img.shields.io/github/stars/Firebasky/CVE-2023-21839">
- [DXask88MA/Weblogic-CVE-2023-21839](https://github.com/DXask88MA/Weblogic-CVE-2023-21839)	<img alt="forks" src="https://img.shields.io/github/forks/DXask88MA/Weblogic-CVE-2023-21839">	<img alt="stars" src="https://img.shields.io/github/stars/DXask88MA/Weblogic-CVE-2023-21839">
- [fakenews2025/CVE-2023-21839](https://github.com/fakenews2025/CVE-2023-21839)	<img alt="forks" src="https://img.shields.io/github/forks/fakenews2025/CVE-2023-21839">	<img alt="stars" src="https://img.shields.io/github/stars/fakenews2025/CVE-2023-21839">
- [dream0x01/weblogic-framework](https://github.com/dream0x01/weblogic-framework)	<img alt="forks" src="https://img.shields.io/github/forks/dream0x01/weblogic-framework">	<img alt="stars" src="https://img.shields.io/github/stars/dream0x01/weblogic-framework">

---
## CVE-2023-2114 (2023-05-08T14:15:00)
> The NEX-Forms WordPress plugin before 8.4 does not properly escape the `table` parameter, which is populated with user input, before concatenating it to an SQL query.
- [SchmidAlex/nex-forms_SQL-Injection-CVE-2023-2114](https://github.com/SchmidAlex/nex-forms_SQL-Injection-CVE-2023-2114)	<img alt="forks" src="https://img.shields.io/github/forks/SchmidAlex/nex-forms_SQL-Injection-CVE-2023-2114">	<img alt="stars" src="https://img.shields.io/github/stars/SchmidAlex/nex-forms_SQL-Injection-CVE-2023-2114">
