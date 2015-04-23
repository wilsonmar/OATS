OATS (Oracle Application Testing Suite)
enables functional and performance testing of Oracle applications.

## <a name="SocialMedia"></a> Social Media

Oracle's marketing home page is at
http://www.oracle.com/technetwork/oem/app-test/etest-101273.html

A LinkedIn group
https://www.linkedin.com/groups/Oracle-Application-Testing-Suite-OATS-2008546

StackOverflow on OATS:
http://stackoverflow.com/search?q=oats
does not have much responses.

Oracle Forums on OATS content:
https://community.oracle.com/search.jspa?q=oats&place=%2Fplaces%2F1284&depth=ALL&customTheme=otn

Twitter: #OracleTest

Facebook?

## <a name="OracleDocs"></a> Oracle's Documents

* Oracle's Getting Started Guide 

	> for version 9.0 for Windows 32-bit (E15487-01, September 2009)

* Oracle Application Testing Suite Release Notes
	
	> Oracle's Release Notes for OATS 9.20 (E17387-03, November 2010) is at
	https://docs.oracle.com/cd/E25294_01/doc.920/e17387/toc.htm#BEGIN

* Oracle Functional Testing for Web Applications Functional Testing User’s Guide
* Oracle Functional Testing for Web Applications Job Scheduler User’s Guide
* Oracle Functional Testing for Web Applications Navigation Editor User’s Guide
* Oracle Functional Testing for Web Applications Application Programming Interface
Reference
* Oracle Functional Testing for Web Applications Result Objects Reference

* Oracle Load Testing for Web Applications Load Testing User’s Guide

* Oracle Test Manager for Web Applications Test Manager User’s Guide

Oracle has a OATS certification Exam 1z0-529 


## <a id="Installers"></a> Installers by Version

Versions are aligned with Oracle apps:

[12.5.0.1.0](#OATS12.5) (current) http://www.oracle.com/technetwork/oem/downloads/index-084446.html

12.4.0.2.0 http://www.oracle.com/technetwork/oem/downloads/apptesting-downloads-1983826.html

12.3.0.1.0 http://www.oracle.com/technetwork/oem/downloads/app-testing-download-2199741.html

The installer generates a password for a specific user during installation.

Trial allows up to 20 vusers to be run.

## <a id="History"></a> History

OATS began as commercial product e-Test from Empirix, which Oracle acquired March, 2008. See
http://www.oracle.com/us/corporate/Acquisitions/empirix/index.html
http://www.oracle.com/us/corporate/press/015619_EN

## <a id="Distinctions"></a> Distinctions

Unlike offerings from HP, SOASTA, etc. that can test a wide variety of systems,
OATS is focused on Oracle apps only and uses only Oracle technologies:

	* Oracle XE (eXpress Edition) Database version 11g Release 2 http://www.oracle.com/technetwork/database/database-technologies/express-edition/overview/index.html
	* Standard WebLogic Server version 10.3.5.0 (with JRocketJDK), not 1035_generic.jar.

Oracle has created **Accelerators** for Oracle Packaged Applications:

	* eBS/FORMS (Oracle e-Business Suite)
	* Siebel
	* JDEEOne
	* Hyperion
	* [Fusion/ADF](http://www.oracle.com/technetwork/developer-tools/adf/overview/index.html)
	* Peoplesoft
	* AdobeFlex

The experienced labor pool is likely to be smaller and thus more expensive
than with HP or other tools.

The download
http://www.oracle.com/technetwork/oem/downloads/index-084446.html
is **for Windows and Linux only**.

	* **Oracle OpenScript for Windows** is also called 
		**Oracle Functional Testing** scripts written in Java using Eclipse IDE.
	* **Oracle Test Manager (OTM)** organizes and manages the testing process.
	* **Oracle Load Testing (OLT)** also includes server side monitoring and reporting
	* **Load Testing Agent** installs also on 32 & 64 bit Windows 2008 R2 and Oracle Enterprise Linux 5 (not Windows 8).

## Alternatives to OATS

The TurnKey Solutions PeopleSoft Accelerator
http://www.turnkeysolutions.com/PeopleSoft-accelerator.php
is based on cFactory™ which Business Process Testing (BPT) objects stored within HP ALM servers.


## <a id="ChangeMgmt"></a> Change / Patch Management
QUESTION: When the system changes, all scripts need to be re-recorded?

QUESTION: Oracle Application Change Management Pack v3 - how does that integrate with

