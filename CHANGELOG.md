## v1.0.0:

* [COOK-1739] - use node attributes with hash notation instead of just
  the attribute name (ipaddress, domain) in djbdns attributes file
* [COOK-1742] - fix foodcritic warnings, use platform_family where
  apropriate

## v0.99.4:

* [COOK-1259] - Support local (10.x, 172.x, 192.168.x) reverse lookups
  in cache

## v0.99.2:

* [COOK-1042] - Corrected a syntax error in axfr.
* [COOK-740] - use correct directory for tinydns root data

## Previous versions:

The various recipes now support multiple service types. This is controlled with the `node[:djbdns][:service_type]` attribute, which is set by platform in the default recipe.

ArchLinux support has been added, as well as naively attempting other platforms by source-compiled installation with bluepill for service management.
