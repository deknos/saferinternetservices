# saferinternetservices
List of demon software for running internet services

## Motivation

there are many services out there which run in languages like C or C++. And in the past these were often plagued by memory management problems.
Because of that i will compile here a list of services which are built in safer languages.

## Is C/C++ bad?

No, it isn't! There are surely usecases for these languages:

- high performance loads
- near or bare metal programming
- building huge applications like games or office applications

But each of these are often commercially backed, and have specific requirements. If you want to run a internet facing service, you want to be at least sure, that the classic problems of the 90ies do not persist that pressing anymore

## Which languages then will you consider "safer"?

This is not a complete list, but my idea would be basically to incorporate:

- Golang
- Rust
- Java
- Ocaml
- Ada

I am currently thinking also including languages like

- Ruby
- Python
- Perl (5/7)

but since these are a little bit more prone to formatstring errors, i am somewhat hesitant to include them.

## i have an issue or suggestion

please write an issue in the repository :)

## Protocols and Service
The list will be the following:
ProjectName - Programming Language - URL 

I will only consider software whose licenses are OSI-approved OpenSource Software and also would like only to name software where there's a independent standard (like RFCs from the IETF) implemented, but there can be exceptions.

### smtp

### imap

### pop3

### ssh

### nntp

### ntp

### sftp

### dns

### http

### xmpp

### irc

### openvpn

### wireguard

### ipsec

### scep

### acme

### OpenID and OAuth2

### ldap

### dhcp

### amqp

### jmap

### dmap

### webdav

### caldav

### kerberos

### nfs

