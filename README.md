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
- PHP

but since these are a little bit more prone to formatstring errors, i am somewhat hesitant to include them.

## i have an issue or suggestion

please write an issue in the repository :)

## Protocols and Service
The list will be the following:
ProjectName - Programming Language - URL 

I will consider adding following software:

- it must has a licensed which is OSI-approved OpenSource Software
- it should implement an independent standard (like RFCs from the IETF for example)
- it should be somewhat production ready and/or tested 
- it should not be just a library which can be used as a server. then we would need examples which implement this and run on this

### smtp

- Go-Guerilla - Golang - https://github.com/flashmob/go-guerrilla
- smtpd - Golang - https://github.com/mhale/smtpd
- chasquid - Golang - https://blitiri.com.ar/p/chasquid/
- gopistolet - Golang - https://github.com/gopistolet/gopistolet
- james - Java - https://james.apache.org/
- mailserver - Java - https://www.ericdaugherty.com/java/mailserver/

### imap

- james - Java - https://james.apache.org/

### pop3

- Popgun - Golang - https://github.com/DevelHell/popgun

### ssh

### nntp

- https://github.com/chrlns/sonews
- https://github.com/timretout/nntp-demo
- https://github.com/miquels/nntp-rs

### ntp

- rust - https://github.com/mlichvar/rsntp
- https://github.com/btfak/sntp

### sftp

- Golang - https://github.com/drakkan/sftpgo
- Java - https://github.com/ggrandes/sftpserver

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

### sip, sdp, rtp, rtsp, ppspp

### i/pxe

### p2p filesharing protocols (e.g. bittorrent, gnutella)

### overlay networks (e.g. ipfs, tor, retroshare, gnunet)

### technical helper implementations (e.g. tlsserver)

### Proxies

- https://github.com/tsurubee/sshr
- https://github.com/izderadicka/ptunnel-rust
- https://github.com/traefik/traefik
- 
