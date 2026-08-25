# pfSense + Wazuh SOC Lab

## Overview

This project is a home SOC lab built with **pfSense, Wazuh, Kali Linux, and Oracle VirtualBox**.

The goal of the lab is to build a small network security monitoring environment where pfSense acts as a firewall, network traffic is logged and forwarded to Wazuh, and Wazuh analyzes the events and generates alerts based on custom detection rules.

## Technologies

* **pfSense 2.9.0** — firewall and network traffic logging
* **Wazuh 4.14.7** — SIEM/XDR and security monitoring
* **Amazon Linux 2023** — Wazuh Manager operating system
* **Kali Linux** — security testing and traffic generation
* **Oracle VirtualBox** — virtualization platform

---

# 1. Wazuh Installation

I downloaded Wazuh components with Linux OS from virtual machine image on [Wazuh documentation](https://documentation.wazuh.com/current/deployment-options/virtual-machine/virtual-machine.html)

Next I rendered IP address assigned to Wazuh Server and used it to access the Wazuh Dashboard from a web browser.

