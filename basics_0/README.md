basics_0

## Overview
This folder contains introductory networking tasks focusing on OSI model, network types, addressing, and simple networking utilities.

## Contents
- 0-OSI_model: Multiple-choice answers about the OSI model
- 1-types_of_network: Multiple-choice answers about network types
- 2-MAC_and_IP_address: Multiple-choice answers about MAC and IP
- 3-UDP_and_TCP: Multiple-choice answers about UDP and TCP
- 4-TCP_and_UDP_ports: Script to display listening ports with PID/program
- 5-is_the_host_on_the_network: Script to ping an IP address 5 times

## Requirements
- Ubuntu 22.04
- Scripts executable, pass shellcheck 0.7.0
- Shebang: `#!/usr/bin/env bash`
- Second line: comment explaining the script purpose

## Usage
- Show listening ports:
```bash
sudo ./4-TCP_and_UDP_ports
```
- Ping a host 5 times:
```bash
./5-is_the_host_on_the_network 8.8.8.8
```
