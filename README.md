# check_snmp_service
Checks the Windows Service over SNMP 


Service Check for Windows Server/Clients

-H
Name or IP address of host (default: 127.0.0.1)

-C 
Community name for the host's SNMP agent (default: public)

-A STRING
Name of Service (default: svchost.exe)

-h
Print this help screen

-V
Print version and license information


This nagios plugins comes with ABSOLUTELY NO WARRANTY.

This plugin uses the 'snmpget' command and the 'snmpwalk' command included with the NET-SNMP package.
This plugin support performance data output.
If the percentage of the warning and critical levels are set 0, then the script returns a OK state.
