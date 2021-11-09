# lanbox

## Definitions

* **User/Users:** Is the person/people consuming LAN resources.
* **Admin/Admins:** Is the person/people administrating the infrastructure

## Planned features

* Ability to serve DHCP requests (kea dhcp)
  * Support for handling switch tftp boot protocol (<https://github.com/dhtech/swboot>)
  * Support for captive portal to force login before access to internet
* Ability to serve DNS requests (PowerDNS)
  * Support for lancache pointers
  * Possible support for auto naming client hostnames
    * Possible support for allowing hostname change by Users
* Ability to Monitor Network, Servers & Applications (Prometheus)
  * Support switch service discovery
  * Support SNMP
  * Support custom application metrics
  * Provide central Dashboard
* Ability for Users to selfservice through a portal (possibly same as the captive portal)
* Ability to serve gameservers (unkown)
  * Supply through Admin portal
  * Supply through User selfservice portal
