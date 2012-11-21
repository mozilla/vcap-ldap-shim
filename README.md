Introduction
------------

This Perl CGI script is a simple way to do LDAP authentication in front
of a CloudFoundry compatible API.

Mozilla is using it in front of CloudFoundry for Petri's Paas Project
and is experimenting with it in front of ActiveState Stackato for
Project Bunsen.

It intercepts certain CF API requests and substitutes an LDAP auth
lookup for the CF builtin authentication. All other API traffic it
proxies through to the CF API endpoint.

Maintainers
------------

This is currently being maintained by Mozilla WebOps. @solarce is the
primary maintainer. Many thanks for gozer for building this.

Installation
------------

Forthcoming...
