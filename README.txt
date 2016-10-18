This plugin can check memory Windows or Linux Server using SNMP v1 queries.

check_snmp_memory is written in Bash and is distributed under the GPLv2 license. This plugin have been created by Yoann LAMY.

Usage: ./check_snmp_memory -H xxx.xxx.xxx.xxx -C public -w 80 -c 90

-H ADDRESS
Name or IP address of host (default: 127.0.0.1)
-C STRING
Community name for the host's SNMP agent (default: public)
-w INTEGER
Warning level for memory in percent (default: 0)
-c INTEGER
Critical level for memory in percent (default: 0)
-h
Print this help screen
-V
Print version and license information

This plugin uses 'snmpget' and 'snmpwalk' commands included with the NET-SNMP package.
This plugin support performance data output. If the percentage of the warning and critical levels are set to 0, then the script returns a OK state.

This nagios plugins comes with ABSOLUTELY NO WARRANTY.

You may redistribute copies of the plugins under the terms of the GNU General Public License v2. 
