<h1>Route Shadow <a href="https://github.com/exaybachay-ak/RouteShadow.ps1/blob/master/shadow.ps1">(Github Link)</a></h1>
<br /><br />
<p>
This code is used as a last-resort penetration test step that should result in buying an additional time window to use for exfiltration, installing backdoors, or any other tactics that you want to utilize to further achieve your project goals.
<br /><br />
Route Shadow occurred to me when we were doing an insider threat simulation/red team assessment, where I thought "Why don't we just re-route detection utilities to $NULL, so we can buy a bit of time to do more stuff until they figure out what's going on?"
<br /><br />
When you run Route Shadow, you need to identify what programs are running that may give away your activities to a SOC or AV platform, and input them into this program.  Then, once you run RouteShadow.ps1, it will gather the IP Addresses they are communicating with, and re-route them to $NULL, effectively cutting off visibiltiy from the SOC.
