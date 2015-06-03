# Icinga2-show-services
## General Information
This is a Perl script which parses Icinga/Nagios status.dat and provides output in text console either services in Critical/Warning state or all services when *--all* option is passed. Output text can be parsed with grep or piped to another program. 

## Usage
Clone this repository and run following command to see all monitored services and corresponding statuses

    perl icinga2_status --all

Verify that your file status.dat exists and the script has access to it

    sudo perl icinga2_status --file /var/cache/icinga2/status.dat

Required Perl modules are
* Getopt::Long
* Term::ANSIColor

Licensing: GPL v2
Support: [Icinga2 www.zhmurko.com](https://www.zhmurko.com/services/icinga2-monitoring/)
