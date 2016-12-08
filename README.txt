Elevate Kit
=========<>
The Elevate Kit demonstrates how to use third-party privilege escalation attacks
with Cobalt Strike's Beacon payload.

Elevate Kit is for Cobalt Strike 3.6 and later. 
https://www.cobaltstrike.com/

Information on Aggressor Script is at: 
https://www.cobaltstrike.com/aggressor-script/

Demonstration video: 
https://www.youtube.com/watch?v=sNKQVchyHDI

How to use
========<>
1. Download this repository
	git clone https://github.com/rsmudge/ElevateKit.git

2. Load elevate.cna into Cobalt Strike. 
	- Go to Cobalt Strike -> Scripts, press Load, select elevate.cna

3. Interact with a Beacon

4. Type 'elevate' to see the list of available privilege escalation attacks.

5. Type 'elevate <exploit name>' to execute an attack

License (elevate.cna)
=====<>
Copyright: 2016, Strategic Cyber LLC
License: BSD-3-clause

Modules
=====<>
The included DLL and .ps1 files are developed by other authors 

ms15-051: Windows ClientCopyImage Win32k Exploit (CVE 2015-1701)
https://github.com/rapid7/metasploit-framework/tree/master/external/source/exploits/cve-2015-1701
https://github.com/rapid7/metasploit-framework/blob/master/modules/exploits/windows/local/ms15_051_client_copy_image.rb

	Author: Unknown, hfirefox, OJ Reeves, Spencer McIntyre
	License: BSD 3-Clause

ms16-016: WebDav Local Privilege Escalation (CVE 2016-0051)
https://github.com/rapid7/metasploit-framework/tree/master/external/source/exploits/cve-2016-0051/dll
https://github.com/rapid7/metasploit-framework/blob/master/modules/exploits/windows/local/ms16_016_webdav.rb

	Author: Tamas Koczka & William Webb
	License: BSD 3-Clause

ms16-032: Secondary Logon Handle Privilege Escalation (CVE-2016-099)
https://github.com/adaptivethreat/Empire/blob/master/data/module_source/privesc/Invoke-MS16032.ps1

	Author: Ruben Boonen (@FuzzySec)
	License: BSD 3-Clause

uac-eventvwr: Bypass UAC with eventvwr.exe
https://github.com/adaptivethreat/Empire/blob/master/data/module_source/privesc/Invoke-EventVwrBypass.ps1

	Author: Matt Nelson (@enigma0x3)
	License: BSD 3-Clause

uac-wscript: Bypass UAC with wscript.exe
https://github.com/adaptivethreat/Empire/blob/master/data/module_source/privesc/Invoke-WScriptBypassUAC.ps1

	Author: @enigma0x3, @harmj0y, Vozzie
	License: BSD 3-Clause
