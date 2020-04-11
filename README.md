# nagiosplugin_piholeapi
A Nagios/Centreon Plugin for Pihole API
![](https://deividsdocs.files.wordpress.com/2020/04/nagios-4-logo.jpg)

## Installation

- Just put it in the folder /usr/lib/nagios/plugin

## Token

- Get the token from the value WEBPASSWORD in the file /etc/pihole/setupVars.conf and put it in /usr/lib/nagios/plugin/apihole.token

## Usage
- Usage $0 -h pihole_ipaddress -s [ clients || queries || ads ] || -i || -q
- s (summary)
 clients: Number of clients using Pihole as their DNS server
 queries: Number of DNS queries
 ads: Number and percentage of ads blocked.
- i (information)
 show the version of the plugin
- q
 queries by type AAAA, A, SOA, TXT, PTR, ANY, SRV, IPV4, IPV6

## More info
Sigue todos los pasos en mi blog
