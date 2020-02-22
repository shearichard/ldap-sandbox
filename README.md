# LDAP-SANDBOX
## Overview
Initially this project provides an LDAP Server and Client in order to investigate the capabilities of a Python based libraries which interact with LDAP.

## What is LDAP ?

*The following is taken from the Wikipedia page for LDAP*

> The Lightweight Directory Access Protocol (LDAP) is an open, vendor-neutral, industry standard application protocol for accessing and maintaining distributed directory information services over an Internet Protocol (IP) network. Directory services play an important role in developing intranet and Internet applications by allowing the sharing of information about users, systems, networks, services, and applications throughout the network. As examples, directory services may provide any organized set of records, often with a hierarchical structure, such as a corporate email directory. Similarly, a telephone directory is a list of subscribers with an address and a phone number. 

## Development Environment

*Mea culpa* I've used Python 3.4 in this project (which is no longer supported) because on the machine I was working I had 3.4 and 3.7 and trying to use 3.7 caused weird problem with SSL when attempting to install one the libraries I wanted to use, specifically python-ldap-test.

The virtualenv on the original dev machine is called `py34ldap`. 


