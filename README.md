# check_snmp_service

**check_snmp_service** is a plugin for checking Windows services over SNMP, designed for monitoring with Nagios and Icinga. This plugin uses the `snmpget` and `snmpwalk` commands from the NET-SNMP package and supports performance data output.

## Usage

The plugin checks if a specific Windows service is available on a server or client and provides status information based on warning and critical thresholds. If the warning and critical thresholds are set to 0, the script automatically returns an OK state.

### Options

| Option      | Description                                                              |
|-------------|--------------------------------------------------------------------------|
| `-H`        | Name or IP address of the host (default: 127.0.0.1)                       |
| `-C`        | Community name for the host's SNMP agent (default: public)                |
| `-A` | Name of the service to be checked (default: svchost.exe)                  |
| `-h`        | Displays this help screen                                                 |
| `-V`        | Prints version and license information                                    |

This Nagios plugin comes with **ABSOLUTELY NO WARRANTY**.

## ICINGA Configuration Files

To use this plugin in Icinga, you can add the following configurations to your Icinga configuration files.
Look in icinga-plugin.txt

This nagios plugins comes with ABSOLUTELY NO WARRANTY.
You may redistribute copies of the plugins under the terms of the GNU General Public License v3.
