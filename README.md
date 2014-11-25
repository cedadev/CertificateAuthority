CertificateAuthority
====================
Provides a simple implementation of a Certificate Authority.  It uses the 
PyOpenSSL for bindings to OpenSSL but also includes the ability to callout 
direct to an ``openssl`` command for more fine-grained control over the certificate 
issuing process if required.

The code has been developed for the Contrail Project, http://contrail-project.eu/

Prerequisites
-------------
This has been developed and tested for Python 2.6 and 2.7.

Installation
------------
Installation can be performed using easy_install or pip.

Configuration
-------------
Examples are contained in ``contrail.security.ca.test``.
